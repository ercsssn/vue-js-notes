<template>
  <div>
    <input type="text" v-model="inputValue">
    
    <p>Five seconds ago, the input said "{{ oldInputValue }}".</p>
  </div>
</template>

<script>

export default {
  name: 'PositiveNumbers',
  data () {
    return {
      inputValue: '',
      oldInputValue: ''
    }
  },
  watch: {
    inputValue() {
      const newValue = this.inputValue;
      setTimeout(() => {
        this.oldInputValue = newValue;
      }, 5000);
    }
  }
}
</script>
