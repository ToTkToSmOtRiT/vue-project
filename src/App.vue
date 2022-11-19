<template>
  <div class="app">
    <Images></Images>
  </div>
</template>

<script>
import Images from './components/ImageSection.vue'
import Comms from './components/Comments.vue'

export default {
  name: 'App',
  components: {
    Images,
    Comms,
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
