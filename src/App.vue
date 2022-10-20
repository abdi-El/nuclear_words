<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <main class="container-fluid h-100">
    <div class="row flex-column justify-content-between h-100">
      <RandomWords class="col-12" />
      <InputBar class="col-12" />
    </div>
  </main>
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

<style lang="scss">
#app {
  height: 100vh;
}
</style>
