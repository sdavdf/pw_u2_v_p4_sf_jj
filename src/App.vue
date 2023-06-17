<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <Contador titulo="Estudiante" valor2="2"/>
  <Contador titulo="Profesor" valor2="2"/>
  <Contador titulo="Test Titulo" valor2="2"/>

</template>

<script>
//Se de be importar ese componente
import Contador from './components/Contador.vue'

export default {
  //Este componente se puede utilizar en diferentes paginas
  //Configurar la opcion components
  name: 'App',
  components: {
    Contador
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
