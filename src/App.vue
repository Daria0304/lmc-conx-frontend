<template>
  <div class="fleet-app">
    <FleetManager />
  </div>
</template>

<script>
import FleetManager from './components/FleetManager.vue'
export default {
  name: 'App',
  components: {
    FleetManager
  }
}
</script>

<style>
body {
  margin: 0;
}
.fleet-app {
  padding: 0;
  margin: 0;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>