<template>
  <div class="_2IrJm">
    <main class="J9UpY _33Bc5">
      <div style="width: 100%; position: relative; height: 100%;">
        <div class="vJADg">
          <div class="_1_RFj">
          </div>
          <Maincontent></Maincontent>
          <MainSlider></MainSlider>
        </div>
      </div>
     </main>
  </div>
</template>

<script>
import Maincontent from './MainContent.vue'
import MainSlider from './MainSlider.vue'
export default {
    components: {
        'Maincontent' : Maincontent,
        'MainSlider' : MainSlider
    }
}
</script>

<style lang="scss">
  @import "/src/assets/scss/container.scss";
</style>
