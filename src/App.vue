<template>


<div cellspacing=0  border=0 style="margin-left:400px; margin-top:130px; position:absolute;  width:550px; height:350px; border-radius:29px; border: 0px solid black; box-shadow:13px 11px 15px 7px rgba(50,50,50,.5); background-image:url('http://wallpapercave.com/wp/wc1701171.jpg'); background-repeat:no-repeat; background-size:cover;" align="center">
      <br><br>
        <fonts class = "card-number"> Card number </fonts>
        <fonts class = "cvv"> CVV </fonts>
        <br>
      <input type="text"pattern = "[0-9]{13,16}" placeholder="•••• •••• •••• ••••"size = "16" class ="input-cardnum">
      <input type="text" pattern = "[0-9]{3,3}" size="3">
      <br>
      <input type="text" class ="input-name" align = "left">
      <br><select style="border-radius:10px; cursor:pointer; width:70px; height:25px; margin-left:-30px;">
        <option>Month</option>
        <option>January</option>
        <option>February</option>
        <option>March</option>
        <option>April</option>
        <option>May</option>
        <option>June</option>
        <option>July</option>
        <option>August</option>
        <option>September</option>
        <option>October</option>
        <option>November</option>
        <option>December</option>
      </select>
      <fonts style="font-family:JasmineUPC; font-weight:bold; font-size:30px; color:white;"> / </fonts>
      <select style="border-radius:10px; cursor:pointer; width:70px; height:25px; margin-left:-5px;">
        <option>Year</option>
        <option>2016</option>
        <option>2017</option>
        <option>2018</option>
        <option>2019</option>
      </select>

</div>

</template>

<script>
import Hello from './components/Hello'

export default {
  name: 'app',
  components: {
    Hello
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.input-cardnum{
  margin-left: -290px;
}

.card-number{
font-family:JasmineUPC;
font-weight:bold;
font-size:20px;
color:white;
text-shadow:
black 0.1em 0.1em 0.2em;
margin-left: -271px;
}

.cvv{
  padding-left: 29px;

  font-family:JasmineUPC;
  font-weight:bold;
  font-size:20px;
  color:white;
  text-shadow: black 0.1em 0.1em 0.2em;
}
.input-name{

}


</style>
