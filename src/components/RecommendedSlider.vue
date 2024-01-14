<template>
    <div class="Recommended_wrap">
        <div class="_1HK9U">
            <div>
                <h3>Recommended products</h3>
            </div>
        </div>
        <div class="-HF5e _3zjAX">
            
                <div class="vue3-carousel__stage">
                    <Carousel v-bind="settings" :breakpoints="breakpoints" :wrap-around="false">
                        <Slide v-for="item in items" :key="item">
                            <div class="vue3-carousel__stage-item">
                                <div class="Cw2rk _3D2o2">
                                    <a class="_2sb7E" data-test-hint="UniversalProductCard-Link-1">
                                        <div class="_2QWVS">
                                            <img :src="item.img"/>
                                        </div>
                                    </a>
                                    <div class="n5aCT">
                                        <a class="_1rsoq" data-test-hint="UniversalProductCard-Link-2" href="#">{{item.title}}</a>
                                        <div class="_2JHn-">
                                            <div class="_2PdIj">{{item.price}}</div>
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
            itemsToShow: 2,
            snapAlign: 'start',
        },
        breakpoints: {
            // 1000px and up
            1000: {
                itemsToShow: 5,
                snapAlign: 'start',
            }
        },
        items: [
          {img: require('../assets/images/sample1.webp'), title: 'Curie Natural Deodorant Stick for Men and Women, Aluminum-Free, Coconut Nectar, 2 oz', price: '$30.21'},
          {img: require('../assets/images/sample2.webp'), title: 'Hellmanns Real Mayonnaise Condiment Real Mayo Gluten Free, Made with 100% Cage-Free Eggs 30 oz', price: '$20.10'},
          {img: require('../assets/images/sample2.jpeg'), title: 'Talk Shop Live New Edition Vision Board Kit', price: '$22.99'},
          {img: require('../assets/images/sample1.jpeg'), title: '8CH 2MP 5MP POE IP Camera Kit HD 1080P H.265...', price: '$28.00'},
          {img: require('../assets/images/sample3.jpeg'), title: 'Valerie Bertinelli - Indulge - Signed', price: '$68.00'},
          {img: require('../assets/images/sample4.webp'), title: 'Quick Prep Cooking - Signed', price: 'from $30.00'},
        ]
      }
    }
  };
</script>

<style lang="scss">
    @import "/src/assets/scss/slider_recommended.scss";
</style>