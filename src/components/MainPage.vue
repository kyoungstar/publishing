<template>
  <div class="wrapper_main">
    <main class="wrapper_inner _33Bc5">
      <div style="width: 100%; position: relative; height: 100%;">
        <div class="wrapper_cont">
          <div class="_1_RFj">
          </div>
          <Maincontents></Maincontents>
          <MainSlider></MainSlider>
        </div>
      </div>
     </main>
  </div>
</template>

<script>
import Maincontents from './MainContents.vue'
import MainSlider from './MainSlider.vue'
export default {
    components: {
        'Maincontents' : Maincontents,
        'MainSlider' : MainSlider
    }
}
</script>

<style lang="scss">
  @import "/src/assets/scss/container.scss";
</style>
