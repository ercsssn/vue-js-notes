<template>
  <div>
    <input type="text" v-model="inputText" value="initial value">
    <p>inputText: {{ inputText }}</p>
  </div>
</template>

<script>

export default {
  name: 'InputText',
  data () {
    return {
      inputText: ''
    }
  }
}
</script>
