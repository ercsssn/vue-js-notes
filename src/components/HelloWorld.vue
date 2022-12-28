<template>
  <div>
    <button v-on:click="increase">Click to increase counter</button>
    <p>You've clicked the button {{ counter }}</p> times.
  </div>
</template>

<script>

export default {
  name: 'PositiveNumbers',
  data () {
    return {
      counter: 0
    }
  },
  methods: {
    increase(e) {
      this.counter++;
    }
  }
}
</script>
