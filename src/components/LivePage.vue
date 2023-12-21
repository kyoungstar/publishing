<template>

    <main class="_3-s0- _1Q26Y">
        <div class="_3WXVr">
            <div class="MWj1A">
                <div class="Kmp12">
                    <div class="_2dAUU" style="height: calc(100vh - 50px); max-height: calc(100vh - 50px);">
                        <div class="_6gcP">
                            <div id="eQf-OF9sCnOT" class="_3Fj_T">
                                <div id="parent-jwplayer" class="U0Wbi _1199X" style="background-image: url(&quot;https://cdn.talkshop.live/eyJidWNrZXQiOiJ0c2wtaW1hZ2VzLXByb2R1Y3Rpb24iLCJrZXkiOiJ2YXJpYW50X2ltYWdlcy83MzY2NTU3L29yaWdpbmFsL3ZhbGVyaWViZXJ0aW5lbGxpLWluZHVsZ2Utc2lnbmVkLmpwZWciLCJlZGl0cyI6eyJyZXNpemUiOnsid2lkdGgiOjIxMzMsImZpdCI6ImNvbnRhaW4ifX19&quot;); height: auto;">
                                    <div id="player-eQf-OF9sCnOT" class="jwplayer jw-reset jw-state-paused jw-stretch-uniform jw-flag-aspect-mode jw-breakpoint-5 jw-floating-dismissible zFSjj jw-flag-autostart jw-flag-user-inactive" tabindex="0" aria-label="Video Player" role="application" style="max-height: calc(100vh - 50px);">
                                        <button type="button" style="color:#fff;background-color: #000;" v-on:click="addSlider()">열렸으면함</button>
                                        <video class="_3EKmG" autoplay="" playsinline="" loop="" id="homepage-sizzle-player" controls="">
                                            <!--<source src="https://assets.talkshop.live/uploads/sizzle.mp4"/>-->
                                        </video>
                                    </div>
                                    <div class="_2mTrh"></div>
                                    <div id="streamViewHeader" class="_2jscc">....</div>
                                    <div id="streamViewFooter" class="wNT4g">...</div>
                                    <div class="_2tIQ0">
                                        <div id="outer-container">
                                            <LiveMenu v-show="leftSlider == true"></LiveMenu>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>

</template>

<script>
import LiveMenu from './LiveMenu.vue'

export default {
    name: 'outer-container',
    components: {
        'LiveMenu' : LiveMenu,
    },
    data() {
        return {
            leftSlider:false
        }
    },
    methods: {
        addSlider() {
            console.log("가고싶다");
            this.leftSlider = true;
        }
    }
}
</script>

<style lang="scss">
  @import "/src/assets/scss/live.scss";
</style>
