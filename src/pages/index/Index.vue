<template>
  <div id="app">
    首页
  </div>
</template>

<script lang="ts">

export default {
  data() {
    return {
      active: 0,
    }
  },
  mounted() {
    console.log(1)
  },
}
</script>

<style lang="scss">
#app {
  height: 100%;
  width: 200px;
  font-size: $font-size;
}
</style>