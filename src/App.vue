<template>
  <div id="app">
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
#app {
  /* 1、cannot resolve */
  background: url("./assets/logo.png");
}

#app {
  /* 2、can resolve */
  background: url("@/assets/logo.png");
}
</style>
