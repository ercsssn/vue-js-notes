<template>
  <div>
    <button @click="divVisible = !divVisible">Toggle visibility</button>

    <transition name="fade">
      <div v-if="divVisible">This content is sometimes hidden</div>
    </transition>
  </div>
</template>

<script>

export default {
  name: 'VuePractice',
  data () {
    return {
      divVisible: true
    }
  }
}
</script>

<style>
  .fade-enter-active, .fade-leave-active {
    transition: opacity .5s;
  }
  .fade-enter, .fade-leave-to {
    opacity: 0;
  }
</style>
