<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    
    <h3>Razas</h3>
    <ul>
        <li><a href="https://www.purina.es/encuentra-mascota/razas-de-perro/shih-tzu" target="_blank" rel="noopener">Shih-tzu</a></li>
        <li><a href="https://www.purina.es/encuentra-mascota/razas-de-perro/pomerania" target="_blank" rel="noopener">Pomerania</a></li>
        <li><a href="https://www.purina.es/encuentra-mascota/razas-de-gato/munchkin" target="_blank" rel="noopener">Munchkin</a></li>
        <li><a href="https://www.purina.es/encuentra-mascota/razas-de-gato/persa-de-pelo-largo" target="_blank" rel="noopener">Persa de pelo largo</a></li>
    </ul>
    <h3>Mascotas</h3>
    <ul>
      <li><a>Rogic</a></li>
      <li><a>Douglas</a></li>
      <li><a>Zeus</a></li>
      <li><a>Nakata</a></li>
      <li><a>Teo</a></li>
    </ul>
    <h3>Productos</h3>
    <ul>
      <li><a href="https://www.purina.es/gatos/comida-gatos" target="_blank" rel="noopener">Comida para gatos</a></li>
      <li><a href="https://www.purina.es/perros/comida-perros" target="_blank" rel="noopener">Comida para perros</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
