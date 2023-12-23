<template>
  <div id="App">
    
    <NeoHeader></NeoHeader>
    <MainPage></MainPage><!--메인페이지-->
    <LoginPage></LoginPage><!--로그인페이지-->
    <CreateChannel></CreateChannel><!--채널만들기-->
    <ChannelDetails></ChannelDetails>
    <NeoFooter></NeoFooter>
    <LivePage></LivePage><!--방송페이지-->
    
  </div>
</template>

<script>
import MainPage from './components/MainPage.vue'
import NeoHeader from './components/NeoHeader.vue'
import LoginPage from './components/LoginPage.vue'
import LivePage from './components/LivePage.vue'
import NeoFooter from './components/NeoFooter.vue'
import CreateChannel from './components/CreateChannel.vue'
import ChannelDetails from './components/ChannelDetails.vue'

export default {
  components: {
    'NeoHeader' : NeoHeader,
    'MainPage' : MainPage,
    'LoginPage' : LoginPage,
    'LivePage' : LivePage,
    'NeoFooter' : NeoFooter,
    'CreateChannel' : CreateChannel,
    'ChannelDetails' : ChannelDetails
  }
}
</script>

<style lang="scss">
 @import "/src/assets/scss/common.scss";
</style>
