<template>
  <div id="app">
    <staff></staff>
  </div>
</template>

<script>
import staff from './views/staff.vue';

export default {
  name: 'App',
  components: {
    staff
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Microsoft Yahei';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
