<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <RandomWords />
  <InputBar />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import RandomWords from './components/RandomWords.vue'
import InputBar from './components/InputBar.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,v
    RandomWords,
    InputBar
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
