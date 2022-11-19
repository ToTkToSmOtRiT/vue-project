<template>
  <div class="app">
    <Images></Images>
    <CommAdd></CommAdd>
  </div>
</template>

<script>
import Images from './components/ImageSection.vue'
import Comms from './components/Comments.vue'
import CommAdd from './components/CommentForm.vue'

export default {
  name: 'App',
  components: {
    Images,
    Comms,
    CommAdd,
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
