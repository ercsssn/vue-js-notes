<template>
  <div id="app">
    <img src="./assets/logo.png">
    <PositiveNumbers/>
  </div>
</template>

<script>
import PositiveNumbers from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    PositiveNumbers
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
