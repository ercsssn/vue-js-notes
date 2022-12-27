<template>
  <div>
  </div>
</template>

<script>

export default {
  name: 'PositiveNumbers',
  data () {
    return {
      value: 10
    }
  },
  computed: {
    doubleValue() {

      console.log('doubleValue computed property changed')

      return this.value * 2;
    }
  }
}
</script>
