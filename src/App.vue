<template>
  <div id="app">
    
    <D3Medo/>
  </div>
</template>

<script>

import D3Medo from './components/D3js/histogram.vue'

export default {
  name: 'app',
  components: {
    D3Medo,
  }
}
</script>

<style>
/* #app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
