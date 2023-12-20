<template>
    <div class="wrapper_login">
        <LoginHeader></LoginHeader>
        <LoginSocial></LoginSocial>
        <LoginForgot></LoginForgot>
    </div>
</template>

<script>
import LoginHeader from './LoginHeader.vue'
import LoginSocial from './LoginSocial.vue'
import LoginForgot from './LoginForgot.vue'

export default {
    components: {
        'LoginHeader' : LoginHeader,
        'LoginSocial' : LoginSocial,
        'LoginForgot' : LoginForgot
    }
}
</script>

<style lang="scss">
  @import "/src/assets/scss/login.scss";
</style>
