<template>
    <main>
        <form class="kdInC" data-test-hint="FindAccountForm-form-1">
            <div class="_2MMj3">Find your account</div>
            <div class="NI-Kb">Enter the email you used to sign up</div>
            <div class="_1McM8 error">
                <div class="_3OaS_">
                    <input name="email" type="text" placeholder="Email" class="_1McM8" id="input-42" value="">
                </div>
                <div class="error_msg">
                    <small>Required</small>
                </div>
            </div>
            <div class="captcha_wrap">
                <!--
                <div data-test-hint="FindAccountForm-ReCAPTCHA-1" style="transform: scale(0.8) translate(12%); transform-origin: 0px 0px;">
                    <div>
                        <div style="width: 304px; height: 78px;">                    
                            <div>
                                <iframe title="reCAPTCHA" width="304" height="78" role="presentation" name="a-jm26elf5udg2" frameborder="0" scrolling="no" sandbox="allow-forms allow-popups allow-same-origin allow-scripts allow-top-navigation allow-modals allow-popups-to-escape-sandbox allow-storage-access-by-user-activation" src="https://www.google.com/recaptcha/api2/anchor?ar=2&amp;k=6Lckd4QhAAAAAJXzH_J59WGDQ6Y_RTSMHRCiq08n&amp;co=aHR0cHM6Ly90YWxrc2hvcC5saXZlOjQ0Mw..&amp;hl=ko&amp;type=image&amp;v=u-xcq3POCWFlCr3x8_IPxgPu&amp;theme=light&amp;size=normal&amp;badge=inline&amp;cb=nafkc74qh8ng">
                                </iframe>
                            </div>
                            <textarea id="g-recaptcha-response-5" name="g-recaptcha-response" class="g-recaptcha-response" style="width: 250px; height: 40px; border: 1px solid rgb(193, 193, 193); margin: 10px 25px; padding: 0px; resize: none; display: none;"></textarea>
                        </div>
                        <iframe style="display: none;"></iframe>
                    </div>
                </div>
                -->
            </div>
            <button class="primary" disabled="">Search</button>
        </form>
    </main>
</template>

<script>
export default {
   
}
</script>

<style lang="scss">
  @import "/src/assets/scss/login_forgot.scss";
</style>
