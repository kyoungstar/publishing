<template>
  <div id="App">
    <NeoHeader></NeoHeader>
    <ContainerMain></ContainerMain>
  </div>
</template>

<script>
import ContainerMain from './components/ContainerMain.vue'
import NeoHeader from './components/NeoHeader.vue'

export default {
  components: {
    'NeoHeader' : NeoHeader,
    'ContainerMain' : ContainerMain
  }
}
</script>

<style lang="scss">
 @import "/src/assets/scss/common.scss";
</style>
