<template>
    <div class="wrapper_login">
        <LoginHeader></LoginHeader>
        <LoginSocial></LoginSocial>
    </div>
</template>

<script>
import LoginHeader from './LoginHeader.vue'
import LoginSocial from './LoginSocial.vue'
export default {
    components: {
        'LoginHeader' : LoginHeader,
        'LoginSocial' : LoginSocial
    }
}
</script>

<style lang="scss">
  @import "/src/assets/scss/login.scss";
</style>
