<template>
  <div id="App">
    <MainHome></MainHome>
  </div>
</template>

<script>
import MainHome from './components/MainHome.vue'
export default {
  components: {
    'MainHome' : MainHome
  }
}
</script>

<style lang="scss" scoped>
@import "/src/assets/scss/main.scss";
</style>
