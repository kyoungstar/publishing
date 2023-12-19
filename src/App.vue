<template>
  <div id="App">
    <NeoHeader></NeoHeader>
    <MainPage></MainPage><!--메인페이지-->
    <LoginPage></LoginPage><!--로그인페이지-->
    <NeoFooter></NeoFooter>
  </div>
</template>

<script>
import MainPage from './components/MainPage.vue'
import NeoHeader from './components/NeoHeader.vue'
import LoginPage from './components/LoginPage.vue'
import NeoFooter from './components/NeoFooter.vue'

export default {
  components: {
    'NeoHeader' : NeoHeader,
    'MainPage' : MainPage,
    'LoginPage' : LoginPage,
    'NeoFooter' : NeoFooter,
  }
}
</script>

<style lang="scss">
 @import "/src/assets/scss/common.scss";
</style>
