<template>
  <div id="app">
    <b-container>
      <Team/>
    </b-container>
  </div>
</template>

<script>
import Team from './components/Team.vue'

export default {
  name: 'App',
  components: {
    Team,
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
