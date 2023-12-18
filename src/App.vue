<template>
  <div id="App">
    <NeoHeader></NeoHeader>
    <ContainerMain></ContainerMain>
    <NeoFooter></NeoFooter>
  </div>
</template>

<script>
import ContainerMain from './components/ContainerMain.vue'
import NeoHeader from './components/NeoHeader.vue'
import NeoFooter from './components/NeoFooter.vue'

export default {
  components: {
    'NeoHeader' : NeoHeader,
    'ContainerMain' : ContainerMain,
    'NeoFooter' : NeoFooter,
  }
}
</script>

<style lang="scss">
 @import "/src/assets/scss/common.scss";
</style>
