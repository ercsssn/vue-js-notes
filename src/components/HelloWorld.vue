<template>
  <p v-if="isMorning">Good morning!</p>
  <p v-else-if="isAfternoon">Good afternoon!</p>
  <p v-else-if="isEvening">Good evening!</p>
</template>

<script>
var hours = new Date().getHours();

export default {
  name: 'HelloWorld',
  data () {
    return {
      isMorning: hours < 12,
      isAfternoon: hours >= 12 && hours < 18,
      isEvening: hours >= 18

    }
  }
}
</script>
