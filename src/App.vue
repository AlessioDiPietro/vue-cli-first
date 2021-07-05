<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Title/>
  </div>
</template>

<script>
import Title from './components/Title.vue'

export default {
  name: 'App',
  components: {
    Title
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: royalblue;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  height: 97vh;
}
</style>
