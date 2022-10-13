<template>
  <img alt="Vue logo3" src="./assets/logo3.jpg">
  <Veterinaria msg="Santiago Restrepo Macias"/>
</template>

<script>
import Veterinaria from './components/Veterinaria.vue'

export default {
  name: 'App',
  components: {
    Veterinaria
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
