<template>
  <div id="App">
    <NeoHeader></NeoHeader>
    <MainHome></MainHome>
  </div>
</template>

<script>
import MainHome from './components/MainHome.vue'
import NeoHeader from './components/NeoHeader.vue'

export default {
  components: {
    'NeoHeader' : NeoHeader,
    'MainHome' : MainHome
  }
}
</script>

<style lang="scss">
 @import "/src/assets/scss/common.scss";
</style>
