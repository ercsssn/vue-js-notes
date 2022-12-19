<template>
  <p v-if="hours < 12">Good morning!</p>
  <p v-else-if="hours >= 12 && hours < 18">Good afternoon!</p>
  <p v-else-if="hours >= 18">Good evening!</p>
</template>

<script>

export default {
  name: 'HelloWorld',
  data () {
    return {
      hours: new Date().getHours()

    }
  }
}
</script>
