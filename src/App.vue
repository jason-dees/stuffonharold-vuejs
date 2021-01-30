<template>
  <div id="app">
    <HaroldContainer />
  </div>
</template>

<script>
import HaroldContainer from './components/HaroldContainer.vue'

export default {
  name: 'App',
  components: {
    HaroldContainer
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
