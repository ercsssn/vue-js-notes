<template>
  <div>
    <form @keyup="handleKeyup">...</form>
  </div>
</template>

<script>

export default {
  name: 'VuePractice',
  data () {
    return {
      counter: 0
    }
  },
  methods: {
    handleKeyup(e) {
      if (e.keyCode === 65) {
        // do something
        console.log('gg');
      }
    }
  }
}
</script>
