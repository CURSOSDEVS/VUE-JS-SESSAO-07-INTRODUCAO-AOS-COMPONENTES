<template>
  <div id="app">
    <h1>Contadores</h1>
    <h1>{{contador}}</h1>
    <button onclick="contador ++">+</button>
  </div>
    
</template>

<script>


export default {
  name: 'App',
  data() {
    return {
      contador: 0
    }
  },
}
</script>

<style>

</style>
