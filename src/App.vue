<template>
  <div id="app">
    <Title/>
    <Main/>
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Main from './components/Main.vue'

export default {
  name: 'App',
  components: {
    Title,
    Main,
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
