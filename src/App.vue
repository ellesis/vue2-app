<template>
  <div id="app">
    <div>
      <h1>vue2-app</h1>
      <img
        alt="Vue logo"
        src="./assets/logo.png"
      />
    </div>
    <hr />

    <!-- highchart -->
    <div>
      <h1>Highchart</h1>
      <RiskEventChart />
    </div>
    <hr />

    <!-- Font awesome -->
    <div>
      <h1>Font awesome - npm i fontawesome</h1>
      <h2>
        <font-awesome-icon icon="fa-solid fa-user-secret" />
        <font-awesome-icon icon="fa-solid fa-circle-question" />
        <font-awesome-icon icon="fa-solid fa-rotate" />
        <font-awesome-icon icon="fa-solid fa-exclamation-triangle" />

        <font-awesome-icon icon="fa-solid fa-video" />
        <font-awesome-icon icon="fa-solid fa-camera" />

        <font-awesome-icon icon="fa-solid fa-battery-three-quarters" />
      </h2>
    </div>
    <hr />

    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
  import HelloWorld from './components/HelloWorld.vue'
  import RiskEventChart from './components/charts/RiskEventChart.vue'

  export default {
    name: 'App',
    components: {
      HelloWorld,
      RiskEventChart
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
