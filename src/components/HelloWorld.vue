<template>
  <div>
    <label><input type="radio" v-model="value" value="one"> One</label>
    <label><input type="radio" v-model="value" value="two"> Two</label>
    <label><input type="radio" v-model="value" value="three"> Three</label>
    <p>The value is {{ value }}</p>
  </div>
</template>

<script>

export default {
  name: 'InputText',
  data () {
    return {
      value: 'one'
    }
  }
}
</script>
