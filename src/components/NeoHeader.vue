<template>
    <nav class="header">
        <div class="header_2RM">
            <div class="_10wKD">
                <div class="_5sz4t">
                    <div class="_3H--o">
                        <a name="visit-home-page-1" class="_3TXr5" data-test-hint="SearchBox-Link-1" href="/"><img src="https://assets.talkshop.live/images/tsl-logo-talkshoplive_r.svg" alt="talkshoplive" height="30" width="158"></a>
                        <div class="_3pGxH">
                            <i class="far fa-search _3t6Z3" aria-hidden="true">
                            </i>                       
                            <input type="search" class="_1Kn4I" placeholder="Search" data-test-hint="SearchBox-input-1" value="">
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <a name="sign-in" class="btn TMMgS" data-role="login-button" href="/login?next=/features/creators">Sign In</a>
        <div class="nav">
            <div class="nav_HCJQe">
                <div class="_2alre">
                    <div @click="toggleVisibleMenu" class="_2qJUS" >
                        <div class="_3-_ci">
                            <div class="nav_wrap">
                                <i class="far fa-bars B3L0S" aria-hidden="true"></i>
                                <!--로그인 후
                                <div class="_1TW9y _1U0Sp">
                                    <span class="_1l4EX _3trbx">ID</span>
                                </div>
                                -->
                            </div>
                        </div>
                    </div>
                    <div class="nav_defalut" :class="{ menushow: isNavPC }">
                        <MenuDesktop></MenuDesktop>
                    </div>
                    <div class="nav_defalut" :class="{ menushow: isNavMb }">
                        <MenuMobile></MenuMobile>
                    </div>
                </div>
                <button aria-label="Open cart" name="open-cart" class="_268AS" data-abbey="VIEW_CART_SIDEBAR'" data-test-hint="MainNav-button-3"><img alt="Cart icon" src="../assets/images/tsl-logo-color.svg" height="16" width="24" data-abbey="VIEW_CART_SIDEBAR'"></button>
            </div>
        </div>
        <div class="bm-overlay nav_defalut" :class="{ menushow: isOverlay }"></div>
    </nav>
</template>

<script>
import MenuDesktop from './MenuDesktop.vue'
import MenuMobile from './MenuMobile.vue'

export default {
    components: {
    'MenuDesktop' : MenuDesktop,
    'MenuMobile' : MenuMobile,
    },
    data() {
        return {
            isNavPC: false,
            isNavMb: false,
            showOverlay: false
        };
    },
    methods: {
        toggleVisibleMenu() {
            var mobileTablet = /Android|Mobile|iP(hone|od|ad)|BlackBerry|IEMobile|Kindle|NetFront|Silk-Accelerated|(hpw|web)OS|Fennec|Minimo|Opera M(obi|ini)|Blazer|Dolfin|Dolphin|Skyfire|Zune/;
            //모바일 일때 모바일 메뉴 활성화
            if (navigator.userAgent.match(mobileTablet)) {
                this.isNavMb = !this.isNavMb;
            //PC 일때 PC메뉴 활성화    
            } else { 
                this.isNavPC = !this.isNavPC;
            }
            //overLay
            this.isOverlay = !this.isOverlay;
        }
    }

}
</script>


<style lang="scss">
  @import "/src/assets/scss/header.scss";
</style>
