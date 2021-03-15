<template>
  <div id="app">
    <Slider />

  </div>
</template>

<script>
import Slider from './components/Slider'

export default {
  name: 'App',
  components: {
    Slider
  }
}
</script>

<style>
#app {
  font-family: 'Montserrat', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color:white;
}
</style>
