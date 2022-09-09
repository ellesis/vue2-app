<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <div>Font awesome</div>
    <h2>
      <font-awesome-icon icon="fa-solid fa-user-secret" />
      <font-awesome-icon icon="fa-solid fa-circle-question" />
      <font-awesome-icon icon="fa-solid fa-rotate" />
      <font-awesome-icon icon="fa-solid fa-exclamation-triangle" />

      <font-awesome-icon icon="fa-solid fa-video" />
      <font-awesome-icon icon="fa-solid fa-camera" />

      <font-awesome-icon icon="fa-solid fa-battery-three-quarters" />
    </h2>

    <i class="fa-solid fa-circle-question"></i>
  </div>
</template>

<script>
  import HelloWorld from './components/HelloWorld.vue'

  export default {
    name: 'App',
    components: {
      HelloWorld
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
