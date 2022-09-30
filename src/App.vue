<template>
  <div>
    <h1>Universidad Tecnologica de Tehuacan 
      <h2>APW</h2>
      <h3>Grupo 3A</h3>

    </h1>
    <h1>Directivas en Vue.js</h1>
    <hr>
    <h2>v.text</h2>
    <span v-text="'JUAS JUAS JUAS'"></span>
    <br>
    <span>Hola desde la directiva v-text</span>
    <br>
    <span v-text="titulo"></span>
    <br>
    Esta es una transmutacion de texto {{titulo}},con una variable prop <br>

    <span v-text="titulo"></span>
    <br>
    Hola hola
    <br>
 

  </div>
</template>
<script>
  export default{
    data:()=>({
      titulo:"Hola desde VUE.js",
    }),
  }
</script>


<style scoped>
  div{
    text-align: center;
    margin: 0px 2rem;
  }
</style>