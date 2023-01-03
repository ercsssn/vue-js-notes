<template>
  <div id="app">
    <img src="./assets/logo.png">
    <display-number v-bind:number="number"></display-number>
  </div>
</template>

<script>
import DisplayNumber from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    DisplayNumber
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
