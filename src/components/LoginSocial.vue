<template>
    <main>
        <div>
            <div class="_1Yh1X">
                <div class="_1vy7g">Sign in</div>
                <div class="_8flC9">
                    <form class="fVtea" data-test-hint="LoginForm-form-1">
                        <div class="_2r3As">
                            <button type="button" class="_8sSv_" data-test-hint="GoogleLoginButton-button-1">
                                <img src="../assets/images/google-g-logo.png" class="_1NLdj">
                                Sign in with Google
                            </button>
                            <button class="_2lpHL" type="button" data-test-hint="LoginForm-button-1">
                                <i class="fa-brands fa-facebook VXDJo _3ErS4" aria-hidden="true"></i>
                                Sign in with Facebook
                            </button>
                            <button class="_2lpHL" type="button" data-test-hint="LoginForm-button-2">
                                <i class="fa fa-apple VXDJo _1PV8z" aria-hidden="true"></i>
                                Sign in with Apple
                            </button>
                        </div>
                        <div class="_1nqya">Or</div>
                        <div class="form-group _1koWZ">
                            <div class="Tw-VL">
                                <div class="_3OaS_">
                                    <input name="email" type="email" placeholder="Email address" class="rUusr" id="input-1" value="">
                                </div>
                            </div>
                            <div class="Tw-VL">
                                <div class="_3OaS_">
                                    <input name="password" type="password" placeholder="Password" class="_2lvkl" id="input-2" value="">
                                </div>
                            </div>
                        </div>
                        <div class="form-group">
                            <div class="_36jCP">
                                <a data-test-hint="LoginForm-Link-1" href="/forgot-password?next=%2Fsettings%2Fcreate-store">
                                    Forgot password?
                                </a>
                            </div>
                        </div>
                        <button data-role="login-button" type="submit" class="PWPP8 W2P3N _3QLI9 _3ZCRK" style="width: 100%; height: 48px;">
                            Sign in
                        </button>
                        <div class="Ho5x9">
                            Need an account?
                        </div>
                        <a class="_2lpHL" data-test-hint="LoginForm-Link-2" href="/register?next=%2Fsettings%2Fcreate-store">
                            Sign up
                        </a>
                    </form>
                </div>
            </div>
        </div>
    </main>
</template>

<script>
export default {
   
}
</script>


<style lang="scss">
  @import "/src/assets/scss/login_social.scss";
</style>
