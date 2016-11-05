<template>


<div cellspacing=0  border=0 style="margin-left:400px; margin-top:130px; position:absolute;  width:550px; height:350px; border-radius:29px; border: 0px solid black; box-shadow:13px 11px 15px 7px rgba(50,50,50,.5); background-image:url('http://wd.thaibuffer.com/o/photo/114/kapook_world-113366.jpg'); background-repeat:no-repeat; background-size:cover;" align="center">
      <br><br>
      <fonts style="font-family:JasmineUPC; font-weight:bold; font-size:30px; color:white; text-shadow: black 0.1em 0.1em 0.2em; margin-left:-140px; "> Cardholder Name </fonts><br>
      <img src="http://www.nuclearwheels.com/images/avatar.png" valign="bottom" style="width:35px;"> <input type="text" style="margin-left:10px; height:25px; width:350px; box-shadow:1px 1px 10px 1px rgba(50,50,50,.5) inset;" placeholder="-cardholder name-">
      <br><br>
      <fonts style="font-family:JasmineUPC; font-weight:bold; font-size:30px; color:white; text-shadow: black 0.1em 0.1em 0.2em; margin-left:-100px; "> Card number </fonts>
      <fonts style="margin-left:180px;font-family:JasmineUPC; font-weight:bold; font-size:30px; color:white; text-shadow: black 0.1em 0.1em 0.2em;"> CODE </fonts>
      <br><input type="text" style="border: 1px gray solid; width:240px; height:25px; margin-left:-8px; box-shadow:1px 1px 10px 1px rgba(50,50,50,.5) inset;" placeholder="-card number-">
      <input type="text" style="margin-left:60px; height:25px; width:150px; box-shadow:1px 1px 10px 1px rgba(50,50,50,.5) inset;" placeholder="-code-"><br><br>
      <fonts style="font-family:JasmineUPC; font-weight:bold; font-size:30px; color:white; text-shadow: black 0.1em 0.1em 0.2em; margin-left:-23px; "> Exp. Date </fonts>
      <fonts style="font-family:JasmineUPC; font-weight:bold; font-size:30px; color:white; text-shadow: black 0.1em 0.1em 0.2em; margin-left:210px; "> CVV </fonts> <fonts style="color:#3300CC; font-weight:bold; font-family:JasmineUPC; font-size:22px;" >(what's this?)</fonts>
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
        <option>2010</option>
        <option>2011</option>
        <option>2012</option>
        <option>2013</option>
        <option>2014</option>
        <option>2015</option>
        <option>2016</option>
      </select>
      <input type="text" style="margin-left:140px; height:25px; width:130px; box-shadow:1px 1px 10px 1px rgba(50,50,50,.5) inset;" placeholder="-cvv-">
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
</style>
