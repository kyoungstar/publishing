<template>
  <div id="App">
    <NeoHeader></NeoHeader>
    <MainPage></MainPage>
    <NeoFooter></NeoFooter>
  </div>
</template>

<script>
import MainPage from './components/MainPage.vue'
import NeoHeader from './components/NeoHeader.vue'
import NeoFooter from './components/NeoFooter.vue'

export default {
  components: {
    'NeoHeader' : NeoHeader,
    'MainPage' : MainPage,
    'NeoFooter' : NeoFooter,
  }
}
</script>

<style lang="scss">
 @import "/src/assets/scss/common.scss";
</style>
