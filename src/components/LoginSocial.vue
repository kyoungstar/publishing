<template>
    <main>
        <div>
            <div class="_1Yh1X">
                <div class="_1vy7g">Sign in</div>
                <!--두 줄인 경우--><div class="_1vy7g">We just need a few more details</div>
                <div class="_8flC9">
                    <form class="fVtea" data-test-hint="LoginForm-form-1">
                        <!--sign IN-->
                        <div class="_2e7y2">
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
                                <a class="_1nL9F" data-test-hint="RegisterView-Link-1" href="/register?email&amp;next=%2F"><i class="fa-solid fa-envelope _1s99Y _2oASt" aria-hidden="true"></i>Sign up with Email</a>
                                <div class="_3-HUY">By signing up, you agree to TalkShopLive's<span><a target="_blank" rel="noopener noreferrer" data-test-hint="RegisterView-Link-2" href="https://support.talkshop.live/hc/en-us/articles/115012106547-Terms-of-Service"> Terms &amp; Conditions</a></span> and <span><a target="_blank" rel="noopener noreferrer" data-test-hint="RegisterView-Link-3" href="https://support.talkshop.live/hc/en-us/articles/115012232647-Privacy-Policy">Privacy Policy</a></span></div>
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
                        </div>
                        <!--//sign IN-->
                        <!--sign UP-->
                        <div class="_2e7y2">
                            <div class="col-xs-12 col-sm mb-sm gyVua">
                                <div class="Tw-VL error">
                                    <div class="_3OaS_">
                                        <input name="first_name" type="text" placeholder="First name" class="_2Vwvm" id="input-18" value="">
                                    </div>
                                    <div class="error_msg"><small>Required</small></div>
                                </div>
                            </div>
                            <div class="col-xs-12 col-sm mb-sm gyVua">
                                <div class="Tw-VL">
                                    <div class="_3OaS_">
                                        <input name="last_name" type="text" placeholder="Last name" class="_2Vwvm" id="input-19" value="">
                                    </div>
                                </div>
                            </div>
                            <div class="col-xs-12 col-sm mb-sm gyVua">
                                <div class="Tw-VL">
                                    <div class="_3OaS_">
                                        <input name="email" type="text" placeholder="Email address" class="_2Vwvm" id="input-20" value="">
                                    </div>
                                </div>
                            </div>
                            <div class="col-xs-12 col-sm mb-sm gyVua">
                                <div class="Tw-VL">
                                    <div class="_3OaS_ nlG8p">
                                        <input name="password" type="password" placeholder="Password" class="_2Vwvm" id="input-21" value="">
                                        <i class="fa-solid fa-eye-slash _3Zs7c" data-test-hint="Input-i-1" aria-hidden="true"></i>
                                        <!--
                                        <i class="fa-solid fa-eye _3Zs7c" data-test-hint="Input-i-1" aria-hidden="true"></i>
                                        -->
                                    </div>
                                </div>
                            </div>
                            <div class="col-xs-12 col-sm mb-sm gyVua">
                                <div class="_3z0gB">
                                    <div class="react-phone-number-input _3lpcf _1G6_G">
                                        <div class="react-phone-number-input__row">
                                            <div class="react-phone-number-input__country react-phone-number-input__country--native">
                                                <div class="react-phone-number-input__icon">
                                                    <img alt="KR" class="react-phone-number-input__icon-image" src="../assets/images/kr.svg">
                                                </div>
                                                <!--
                                                <select name="phone__country" aria-label="Country" class="react-phone-number-input__country-select"><option value="ZZ">International</option><option value="AF">Afghanistan (&#x202B;افغانستان&#x202C;&lrm;)</option><option value="AX">Åland Islands</option><option value="AL">Albania (Shqipëri)</option><option value="DZ">Algeria (&#x202B;الجزائر&#x202C;&lrm;)</option><option value="AS">American Samoa (Amerika Sāmoa)</option><option value="AD">Andorra</option><option value="AO">Angola</option><option value="AI">Anguilla</option><option value="AG">Antigua and Barbuda</option><option value="AR">Argentina</option><option value="AM">Armenia (Հայաստան)</option><option value="AW">Aruba</option><option value="AC">Ascension Island</option><option value="AU">Australia</option><option value="AT">Austria (Österreich)</option><option value="AZ">Azerbaijan (Azərbaycan)</option><option value="BS">Bahamas</option><option value="BH">Bahrain (&#x202B;البحرين&#x202C;&lrm;)</option><option value="BD">Bangladesh (বাংলাদেশ)</option><option value="BB">Barbados</option><option value="BY">Belarus (Беларусь)</option><option value="BE">Belgium (België)</option><option value="BZ">Belize</option><option value="BJ">Benin (Bénin)</option><option value="BM">Bermuda</option><option value="BT">Bhutan (འབྲུག)</option><option value="BO">Bolivia</option><option value="BA">Bosnia and Herzegovina</option><option value="BW">Botswana</option><option value="BR">Brazil (Brasil)</option><option value="IO">British Indian Ocean Territory</option><option value="VG">British Virgin Islands</option><option value="BN">Brunei (Negara Brunei Darussalam)</option><option value="BG">Bulgaria (България)</option><option value="BF">Burkina Faso</option><option value="BI">Burundi (Uburundi)</option><option value="KH">Cambodia (កម្ពុជា)</option><option value="CM">Cameroon (Cameroun)</option><option value="CA">Canada</option><option value="CV">Cape Verde (Kabu Verdi)</option><option value="BQ">Caribbean Netherlands</option><option value="KY">Cayman Islands</option><option value="CF">Central African Republic</option><option value="TD">Chad (Tchad)</option><option value="CL">Chile</option><option value="CN">China (中国)</option><option value="CX">Christmas Island</option><option value="CC">Cocos (Keeling) Islands</option><option value="CO">Colombia</option><option value="KM">Comoros (&#x202B;جزر القمر&#x202C;&lrm;)</option><option value="CD">Congo (DRC) (Kongo)</option><option value="CG">Congo (Republic) (Congo-Brazzaville)</option><option value="CK">Cook Islands</option><option value="CR">Costa Rica</option><option value="CI">Côte d’Ivoire</option><option value="HR">Croatia (Hrvatska)</option><option value="CU">Cuba</option><option value="CW">Curaçao</option><option value="CY">Cyprus (Κύπρος)</option><option value="CZ">Czech Republic (Česká republika)</option><option value="DK">Denmark (Danmark)</option><option value="DJ">Djibouti</option><option value="DM">Dominica</option><option value="DO">Dominican Republic</option><option value="EC">Ecuador</option><option value="EG">Egypt (&#x202B;مصر&#x202C;&lrm;)</option><option value="SV">El Salvador</option><option value="GQ">Equatorial Guinea (Guinea Ecuatorial)</option><option value="ER">Eritrea</option><option value="EE">Estonia (Eesti)</option><option value="ET">Ethiopia</option><option value="FK">Falkland Islands (Islas Malvinas)</option><option value="FO">Faroe Islands (Føroyar)</option><option value="FJ">Fiji (Matanitu Tugalala o Viti)</option><option value="FI">Finland (Suomi)</option><option value="FR">France (République française)</option><option value="GF">French Guiana (Guyane française)</option><option value="PF">French Polynesia (Polynésie française)</option><option value="GA">Gabon (République gabonaise)</option><option value="GM">Gambia</option><option value="GE">Georgia (საქართველო)</option><option value="DE">Germany (Deutschland)</option><option value="GH">Ghana (Gaana)</option><option value="GI">Gibraltar</option><option value="GR">Greece (Ελλάδα)</option><option value="GL">Greenland (Kalaallit Nunaat)</option><option value="GD">Grenada</option><option value="GP">Guadeloupe</option><option value="GU">Guam (Guåhån)</option><option value="GT">Guatemala</option><option value="GG">Guernsey</option><option value="GN">Guinea (Guinée)</option><option value="GW">Guinea-Bissau (Guiné Bissau)</option><option value="GY">Guyana</option><option value="HT">Haiti (République d'Haïti)</option><option value="HN">Honduras</option><option value="HK">Hong Kong (香港)</option><option value="HU">Hungary (Magyarország)</option><option value="IS">Iceland (Ísland)</option><option value="IN">India (भारत)</option><option value="ID">Indonesia</option><option value="IR">Iran (&#x202B;ایران&#x202C;&lrm;)</option><option value="IQ">Iraq (&#x202B;العراق&#x202C;&lrm;)</option><option value="IE">Ireland</option><option value="IM">Isle of Man</option><option value="IL">Israel (&#x202B;ישראל&#x202C;&lrm;)</option><option value="IT">Italy (Italia)</option><option value="JM">Jamaica</option><option value="JP">Japan (日本)</option><option value="JE">Jersey</option><option value="JO">Jordan (&#x202B;الأردن&#x202C;&lrm;)</option><option value="KZ">Kazakhstan (Казахстан)</option><option value="KE">Kenya</option><option value="KI">Kiribati</option><option value="XK">Kosovo</option><option value="KW">Kuwait (&#x202B;الكويت&#x202C;&lrm;)</option><option value="KG">Kyrgyzstan (Кыргызстан)</option><option value="LA">Laos (ລາວ)</option><option value="LV">Latvia (Latvija)</option><option value="LB">Lebanon (&#x202B;لبنان&#x202C;&lrm;)</option><option value="LS">Lesotho</option><option value="LR">Liberia</option><option value="LY">Libya (&#x202B;ليبيا&#x202C;&lrm;)</option><option value="LI">Liechtenstein</option><option value="LT">Lithuania (Lietuva)</option><option value="LU">Luxembourg (Lëtzebuerg)</option><option value="MO">Macau (澳門)</option><option value="MK">Macedonia (FYROM) (Македонија)</option><option value="MG">Madagascar (Madagasikara)</option><option value="MW">Malawi (Malaŵi)</option><option value="MY">Malaysia</option><option value="MV">Maldives</option><option value="ML">Mali</option><option value="MT">Malta</option><option value="MH">Marshall Islands</option><option value="MQ">Martinique</option><option value="MR">Mauritania (&#x202B;موريتانيا&#x202C;&lrm;)</option><option value="MU">Mauritius (Moris)</option><option value="YT">Mayotte</option><option value="MX">Mexico (México)</option><option value="FM">Micronesia</option><option value="MD">Moldova (Republica Moldova)</option><option value="MC">Monaco</option><option value="MN">Mongolia (Монгол)</option><option value="ME">Montenegro (Crna Gora)</option><option value="MS">Montserrat</option><option value="MA">Morocco (&#x202B;المغرب&#x202C;&lrm;)</option><option value="MZ">Mozambique (Moçambique)</option><option value="MM">Myanmar (Burma) (မြန်မာ)</option><option value="NA">Namibia (Namibië)</option><option value="NR">Nauru (Repubrikin Naoero)</option><option value="NP">Nepal (नेपाल)</option><option value="NL">Netherlands (Nederland)</option><option value="NC">New Caledonia (Nouvelle-Calédonie)</option><option value="NZ">New Zealand</option><option value="NI">Nicaragua</option><option value="NE">Niger (Nijar)</option><option value="NG">Nigeria</option><option value="NU">Niue (Niuē)</option><option value="NF">Norfolk Island</option><option value="KP">North Korea (조선 민주주의 인민 공화국)</option><option value="MP">Northern Mariana Islands</option><option value="NO">Norway (Norge)</option><option value="OM">Oman (&#x202B;عُمان&#x202C;&lrm;)</option><option value="PK">Pakistan (&#x202B;پاکستان&#x202C;&lrm;)</option><option value="PW">Palau (Beluu er a Belau)</option><option value="PS">Palestine (&#x202B;فلسطين&#x202C;&lrm;)</option><option value="PA">Panama (Panamá)</option><option value="PG">Papua New Guinea</option><option value="PY">Paraguay (Tetã Paraguái)</option><option value="PE">Peru (Perú)</option><option value="PH">Philippines (Republika ng Pilipinas)</option><option value="PL">Poland (Polska)</option><option value="PT">Portugal (República Portuguesa)</option><option value="PR">Puerto Rico</option><option value="QA">Qatar (&#x202B;قطر&#x202C;&lrm;)</option><option value="RE">Réunion (La Réunion)</option><option value="RO">Romania (România)</option><option value="RU">Russia (Россия)</option><option value="RW">Rwanda</option><option value="BL">Saint Barthélemy (Saint-Barthélemy)</option><option value="SH">Saint Helena</option><option value="KN">Saint Kitts and Nevis</option><option value="LC">Saint Lucia</option><option value="MF">Saint Martin (Saint-Martin)</option><option value="PM">Saint Pierre and Miquelon</option><option value="VC">Saint Vincent and the Grenadines</option><option value="WS">Samoa (Sāmoa)</option><option value="SM">San Marino</option><option value="ST">São Tomé and Príncipe</option><option value="SA">Saudi Arabia (&#x202B;المملكة العربية السعودية&#x202C;&lrm;)</option><option value="SN">Senegal (Sénégal)</option><option value="RS">Serbia (Србија)</option><option value="SC">Seychelles (Repiblik Sesel)</option><option value="SL">Sierra Leone</option><option value="SG">Singapore (Singapura) (新加坡共和国)</option><option value="SX">Sint Maarten</option><option value="SK">Slovakia (Slovensko)</option><option value="SI">Slovenia (Slovenija)</option><option value="SB">Solomon Islands</option><option value="SO">Somalia (Soomaaliya)</option><option value="ZA">South Africa</option><option value="KR">South Korea (대한민국)</option><option value="SS">South Sudan (&#x202B;جنوب السودان&#x202C;&lrm;)</option><option value="ES">Spain (España)</option><option value="LK">Sri Lanka (ශ්&zwj;රී ලංකාව)</option><option value="SD">Sudan (&#x202B;السودان&#x202C;&lrm;)</option><option value="SR">Suriname</option><option value="SJ">Svalbard and Jan Mayen</option><option value="SZ">Swaziland (Umbuso weSwatini)</option><option value="SE">Sweden (Sverige)</option><option value="CH">Switzerland (Schweiz)</option><option value="SY">Syria (&#x202B;سوريا&#x202C;&lrm;)</option><option value="TW">Taiwan (台灣)</option><option value="TJ">Tajikistan (Ҷумҳурии Тоҷикистон)</option><option value="TZ">Tanzania</option><option value="TH">Thailand (ไทย)</option><option value="TL">Timor-Leste (Timór-Leste)</option><option value="TG">Togo (République togolaise)</option><option value="TK">Tokelau</option><option value="TO">Tonga</option><option value="TT">Trinidad and Tobago</option><option value="TA">Tristan da Cunha</option><option value="TN">Tunisia (&#x202B;تونس&#x202C;&lrm;)</option><option value="TR">Turkey (Türkiye)</option><option value="TM">Turkmenistan (Türkmenistan)</option><option value="TC">Turks and Caicos Islands</option><option value="TV">Tuvalu</option><option value="VI">U.S. Virgin Islands</option><option value="UG">Uganda</option><option value="UA">Ukraine (Україна)</option><option value="AE">United Arab Emirates (&#x202B;الإمارات العربية المتحدة&#x202C;&lrm;)</option><option value="GB">United Kingdom</option><option value="US">United States</option><option value="UY">Uruguay</option><option value="UZ">Uzbekistan (Oʻzbekiston)</option><option value="VU">Vanuatu</option><option value="VA">Vatican City (Città del Vaticano)</option><option value="VE">Venezuela</option><option value="VN">Vietnam (Việt Nam)</option><option value="WF">Wallis and Futuna (Wallis-et-Futuna)</option><option value="EH">Western Sahara (&#x202B;الصحراء الغربية&#x202C;&lrm;)</option><option value="YE">Yemen (&#x202B;اليمن&#x202C;&lrm;)</option><option value="ZM">Zambia</option><option value="ZW">Zimbabwe</option>
                                                </select>
                                                <div class="react-phone-number-input__country-select-arrow"></div>-->
                                            </div>
                                            <input type="tel" autocomplete="tel" name="phone" placeholder="Mobile number" data-test-hint="Phone-PhoneInput-1" class="react-phone-number-input__input react-phone-number-input__phone" value="">
                                        </div>
                                    </div>
                                    <div class="rpODC">Optional</div>
                                </div>
                            </div>
                            <div class="_2tV7D">
                                <div class="gyVua">
                                    <div class="uexdn">
                                        <div class="Select _2dqI1 Select--single is-searchable">
                                            <input name="day" maxlength="2" type="text" placeholder="Month" class="_2Vwvm" id="input-11" value="">
                                        </div>
                                    </div>
                                </div>
                                <div class="gyVua">
                                    <div class="Tw-VL">
                                        <div class="_3OaS_">
                                            <input name="day" maxlength="2" type="text" placeholder="Day" class="_2Vwvm" id="input-22" value="">
                                        </div>
                                    </div>
                                </div>
                                <div class="gyVua">
                                    <div class="Tw-VL">
                                        <div class="_3OaS_">
                                            <input name="year" maxlength="4" type="text" placeholder="Year" class="_2Vwvm" id="input-23" value="">
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!--//sign UP-->
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
