<template>
  <p>The number is {{ number }}</p>
</template>

<script>

export default {
  name: 'display-number',
  created() {
    setInterval(() => {
      this.number++;
    }, 1000);
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      number: 0
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
