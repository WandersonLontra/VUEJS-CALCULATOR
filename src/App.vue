<template>
  <div id="app">
    <h1>Calculadora</h1>

    <Calculator />
  </div>
</template>

<script>
  import Calculator from "./main/Calculator.vue";

  export default {
    components: {Calculator}
  }
</script>

<style>
  @font-face {
    font-family: "RobotoMono";
    src: url("./fonts/RobotoMono-Thin.ttf");
  }
  
  body{
    margin: 0;
    padding: 0;
  }

  #app{
    font-family: "RobotoMono", Helvetica, Arial, sans-serif;
    display: flex;
    flex-direction: column;
    height: 100vh;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: #FFF;

    background: linear-gradient(to right, rgb(83,108,118), rgb(41,46,73));
  }
</style>



