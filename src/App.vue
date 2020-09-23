<template>
  <div id="app">
  Hi!
  <Erik class="blah"/>
  </div>
</template>

<script>
import Erik from '~/src/components/Erik.vue';

export default {
  
  name: 'App',
  components: {
    Erik
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
