<template>
    <div class="_14kIw vOVaW">
        <h2>New &amp; upcoming</h2>
        <div class="-HF5e _3ZKs_">
            
            <div class="vue3-carousel__stage">
                <Carousel v-bind="settings" :breakpoints="breakpoints" :wrap-around="false">
                    <Slide v-for="item in items" :key="item">
                    
                        <div class="vue3-carousel__stage-item">
                            <div class="_3HFcX">
                                <div class="V3D_d">
                                    <a class="wHpww" data-test-hint="UniversalShowCard-Link-1" href="/watch/vcVds3INGO-z">
                                        <div class="_114Vk">
                                            <img :src="item.img"/>
                                        </div>
                                    </a>
                                    <div class="_2hEzG">
                                        <a class="_1oz5H" data-test-hint="UniversalShowCard-Link-2" href="/channels/channel3">
                                            <div class="_1TW9y _1U0Sp">
                                                <img alt="Avatar image" class="_2qclA _3gH7F" :src="item.avt"/>
                                            </div>
                                        </a>
                                        <div class="_2YrAy">
                                            <div class="_1b5Q9 _1YWAI">
                                                <div class="_1x-tW">
                                                    <b>{{item.date}}</b> at {{item.time}}
                                                </div>
                                                <div>
                                                    <a class="_2jfOQ _2QGNk LkySA" data-test-hint="UniversalFollowButton-Link-1">
                                                        <i class="fa-solid fa-bell _35vsF" aria-hidden="true"></i>Notify me
                                                    </a>
                                                </div>
                                            </div>
                                            <a class="_12Af-" data-test-hint="UniversalShowCard-Link-3" href="/watch/vcVds3INGO-z">{{item.title}}</a>
                                            <a class="_1nlN6 standaloneTextButton" data-test-hint="UniversalShowCard-Link-4" href="/channels/channel3">{{item.link}}</a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </Slide>

                    <template #addons>
                        <Navigation />
                    </template>
                </Carousel>
            </div>

        </div>
    </div>
</template>

<script>

import { Carousel, Navigation, Slide } from 'vue3-carousel'
import 'vue3-carousel/dist/carousel.css'

export default {
    name: 'BreakPoints',
    components: {
        Carousel,
        Slide,
        Navigation,
    },
    data() {
      return {
        settings: {
            itemsToShow: 1,
            snapAlign: 'start',
        },
        breakpoints: {
            // 1000px and up
            1000: {
                itemsToShow: 3,
                snapAlign: 'start',
            },
            // 1600px and up
            1600: {
                itemsToShow: 5,
                snapAlign: 'start',
            }
        },
        items: [
          {img: require('../assets/images/slider_t1.jpg'), title: 'Happy Hour IG Live', link: 'Channel3', avt: require('../assets/images/slider_t1_avt.png'), date: 'Nov 16th, 2024', time: '3:34am'},
          {img: require('../assets/images/slider_t2.jpg'), title: 'New Year, New Look!', link: 'smartcookies', avt: require('../assets/images/slider_t2_avt.jpg'), date: 'Nov 16th, 2024', time: '3:34am'},
          {img: require('../assets/images/slider_t3.jpg'), title: 'Holiday Goodies', link: 'Mike "The Situation"', avt: require('../assets/images/slider_t3_avt.jpg'), date: 'Nov 16th, 2024', time: '3:34am'},
          {img: require('../assets/images/slider_t4.jpg'), title: '2023 Luxury Review Box!', link: 'NewBeauty', avt: require('../assets/images/slider_t4_avt.jpg'), date: 'Nov 16th, 2024', time: '3:34am'},
          {img: require('../assets/images/slider_t5.jpg'), title: 'Smile brighter and whiter!', link: 'linhartnyc', avt: require('../assets/images/slider_t5_avt.png'), date: 'Nov 16th, 2024', time: '3:34am'},
          {img: require('../assets/images/slider_t6.jpg'), title: 'Holiday Goodies', link: 'Mike "The Situation"', avt: require('../assets/images/slider_t2_avt.jpg'), date: 'Nov 16th, 2024', time: '3:34am'},
        ]
      }
    }
  };
</script>

<style lang="scss">
    @import "/src/assets/scss/slider.scss";
</style>