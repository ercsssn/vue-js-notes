<template>
  <div>
    <ul>
      <li v-for="number in filterPositive(numbers)">{{ number }}</li>
    </ul>
  </div>
</template>

<script>

export default {
  name: 'PositiveNumbers',
  data () {
    return {
      numbers: [-5, 0, 2, -1, 1, 0.5]
    }
  },
  methods: {
    filterPositive(numbers) {
      return numbers.filter((number) => number >= 0);
    }
  }
}
</script>
