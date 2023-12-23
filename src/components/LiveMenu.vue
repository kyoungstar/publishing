<template>
    <div id="" class="live-menu-wrap"  v-bind:class="{hideLeft: showLeft == 'false'}" aria-hidden="false">
        <div class="live-menu" style="height: 100%; box-sizing: border-box; overflow: auto;">
            <nav class="live-item-list" style="height: 100%;">
                
                <div class="live-item _3P0DQ" tabindex="-1" style="display: block;">
                    <button v-on:click="hideSlider()" name="collapse-menu" class="_1mm4Q" data-abbey="COLLAPSE_SIDEBAR" data-test-hint="StreamView-button-1">
                        <i class="fa fa-chevron-right" data-abbey="COLLAPSE_SIDEBAR" aria-hidden="true"></i>
                    </button>
                    <div id="tab-container" class="_144Pt">
                        <!--상단메뉴 Start-->
                        <div class="_1GUBJ">
                            <div class="tab_live" id="tab_live">
                                <button v-bind:class="{active: currentTab === 0}" 
                                     v-on:click="currentTab = 0" id="tab-chat" role="tab" aria-selected="true" aria-controls="tabpanel-chat" class="_1qrzX _3ZTD-" data-abbey="SELECT_VIEW_CHAT_SIDEBAR">
                                    <span data-abbey="SELECT_VIEW_CHAT_SIDEBAR">Chat</span>
                                </button>
                                <button v-bind:class="{active: currentTab === 1}" 
                                     v-on:click="currentTab = 1" id="tab-details" role="tab" aria-selected="false" aria-controls="tabpanel-details" class="_1qrzX _3ZTD-" data-abbey="SELECT_VIEW_DETAILS_SIDEBAR" style="">
                                    <span data-abbey="SELECT_VIEW_DETAILS_SIDEBAR">Details</span>
                                </button>
                                <button v-bind:class="{active: currentTab === 2}" 
                                     v-on:click="currentTab = 2" id="tab-buy" role="tab" aria-selected="true" aria-controls="tabpanel-buy" class="_1qrzX _3ZTD-" data-abbey="VIEW_ALL_PRODUCTS">
                                    <span data-abbey="VIEW_ALL_PRODUCTS">Shop</span>
                                </button>
                            </div>
                        </div>
                        <!--상단메뉴 End-->
                        <!--Chat Start-->
                        <div v-show="currentTab == 0" id="tabpanel-chat" role="tabpanel" aria-labelledby="tab-chat" class="_2t2Nu tab-content-visible">
                            <div class="pn-msg-list pn-msg-list--light" id="messages-list">
                                <div class="pn-msg-list-scroller pn-msg-list-scroller-smooth">
                                    <div class="message-item-container pn-msg">
                                        <div class="pn-ms-comment  "><div class="pn-msg-right-side"><div class="pn-msg-top-side"><span class="pn-msg-list-avatar"><span class="pn-msg-avatar">MA</span></span><div class="pn-msg__main"><div class="pn-msg-list-arrow"></div><div class="pn-msg-custom-actions"><button class="png-msg__add-remove-action" title="Like" data-test-hint="MessageItemCustomActions-button-2" data-abbey="LIKE_COMMENT"><i class="fa fa-heart-o pn-heart-icon" aria-hidden="true" data-abbey="LIKE_COMMENT"></i></button></div><div class="pn-msg__content"><div class="pn-msg__message"><span class="pn-msg__author"><a class="" data-test-hint="MessageItemBody-Link-1">Marion</a></span>OMG Valerie, love you so much!</div><div class="pn-msg__footer"><span>2m</span> <span class="pn-likes-count">1 like</span></div></div></div></div><div class="pn-ms-answer"></div></div></div>
                                    </div>
                                    
                                    <div class="message-item-container pn-msg">
                                        <div class="pn-ms-comment  "><div class="pn-msg-right-side"><div class="pn-msg-top-side"><span class="pn-msg-list-avatar"><img class="pn-msg-avatar-image" alt="profile-pic-HR" src="https://cdn.talkshop.live/eyJidWNrZXQiOiJ0c2wtaW1hZ2VzLXByb2R1Y3Rpb24iLCJrZXkiOiJhdmF0YXJzLzI5NjI0L29yaWdpbmFsL0lNR18yMDIwMDIwNF8xNDA4NDYuanBnIiwiZWRpdHMiOnsicmVzaXplIjp7IndpZHRoIjoxMDAsImhlaWdodCI6MTAwLCJmaXQiOiJmaWxsIn19fQ==" data-test-hint="MessageItem-img-1"></span><div class="pn-msg__main"><div class="pn-msg-list-arrow"></div><div class="pn-msg-custom-actions"><button class="png-msg__add-remove-action" title="Like" data-test-hint="MessageItemCustomActions-button-2" data-abbey="LIKE_COMMENT"><i class="fa fa-heart-o pn-heart-icon" aria-hidden="true" data-abbey="LIKE_COMMENT"></i></button></div><div class="pn-msg__content"><div class="pn-msg__message"><span class="pn-msg__author"><a class="" data-test-hint="MessageItemBody-Link-1">Henrietta R</a></span>Hi Valerie! Congrats on your book!</div><div class="pn-msg__footer"><span>2m</span> <span class="pn-likes-count">1 like</span></div></div></div></div><div class="pn-ms-answer"></div></div></div>
                                    </div>
                                    
                                    <div class="message-item-container pn-msg">
                                        <div class="pn-ms-comment  "><div class="pn-msg-right-side"><div class="pn-msg-top-side"><span class="pn-msg-list-avatar"><span class="pn-msg-avatar">LL</span></span><div class="pn-msg__main"><div class="pn-msg-list-arrow"></div><div class="pn-msg-custom-actions"><button data-abbey="LIKE_COMMENT" class="png-msg__add-remove-action" title="Like" data-test-hint="MessageItemCustomActions-button-2"><i data-abbey="LIKE_COMMENT" class="fa fa-heart-o pn-heart-icon" aria-hidden="true"></i></button></div><div class="pn-msg__content"><div class="pn-msg__message"><span class="pn-msg__author"><a class="" data-test-hint="MessageItemBody-Link-1">Linda L</a></span>Hi Valerie !!</div><div class="pn-msg__footer"><span>2m</span> <span class="pn-likes-count">1 like</span></div></div></div></div><div class="pn-ms-answer"></div></div></div>
                                    </div>
                                    
                                    <div class="message-item-container pn-msg">
                                        <div class="pn-ms-comment  "><div class="pn-msg-right-side"><div class="pn-msg-top-side"><span class="pn-msg-list-avatar"><span class="pn-msg-avatar">NB</span></span><div class="pn-msg__main pn-msg__is-question"><div class="pn-msg-list-arrow"></div><div class="pn-msg-custom-actions"><button class="png-msg__add-remove-action" title="Like" data-test-hint="MessageItemCustomActions-button-2" data-abbey="LIKE_COMMENT"><i class="fa fa-heart-o pn-heart-icon" aria-hidden="true" data-abbey="LIKE_COMMENT"></i></button></div><div class="pn-msg__content"><div class="pn-msg__message"><span class="pn-msg__question">?</span><span class="pn-msg__author"><a class="" data-test-hint="MessageItemBody-Link-1">Nina B</a></span>정말 좋지 않나요? </div><div class="pn-msg__footer"><span>2m</span> <span class="pn-likes-count">1 like</span></div></div></div></div><div class="pn-ms-answer"></div></div></div>
                                    </div>
                                    
                                    <div class="message-item-container pn-msg">
                                        <div class="pn-ms-comment  "><div class="pn-msg-right-side"><div class="pn-msg-top-side"><span class="pn-msg-list-avatar"><span class="pn-msg-avatar">MA</span></span><div class="pn-msg__main pn-msg__is-question"><div class="pn-msg-list-arrow"></div><div class="pn-msg-custom-actions"><button data-abbey="LIKE_COMMENT" class="png-msg__add-remove-action" title="Like" data-test-hint="MessageItemCustomActions-button-2"><i data-abbey="LIKE_COMMENT" class="fa fa-heart-o pn-heart-icon" aria-hidden="true"></i></button></div><div class="pn-msg__content"><div class="pn-msg__message"><span class="pn-msg__question">?</span><span class="pn-msg__author"><a class="" data-test-hint="MessageItemBody-Link-1">Marion</a></span>How many books does this make for you now?</div><div class="pn-msg__footer"><span>2m</span> <span class="pn-likes-count">1 like</span></div></div></div></div><div class="pn-ms-answer"></div></div></div>
                                    </div>
                                    
                                    <div class="message-item-container pn-msg">
                                        <div class="pn-ms-comment  "><div class="pn-msg-right-side"><div class="pn-msg-top-side"><span class="pn-msg-list-avatar"><img class="pn-msg-avatar-image" alt="profile-pic-NS" src="https://cdn.talkshop.live/eyJidWNrZXQiOiJ0c2wtaW1hZ2VzLXByb2R1Y3Rpb24iLCJrZXkiOiJhdmF0YXJzLzE2MjIyNC9vcmlnaW5hbC85YWU5ZDJkNy05ODM0LTRjYzktODE1NC05YzkwMzEzYmRlMDMiLCJlZGl0cyI6eyJyZXNpemUiOnsid2lkdGgiOjEwMCwiaGVpZ2h0IjoxMDAsImZpdCI6ImZpbGwifX19" data-test-hint="MessageItem-img-1"></span><div class="pn-msg__main"><div class="pn-msg-list-arrow"></div><div class="pn-msg-custom-actions"><button class="png-msg__add-remove-action" title="Like" data-test-hint="MessageItemCustomActions-button-2" data-abbey="LIKE_COMMENT"><i class="fa fa-heart-o pn-heart-icon" aria-hidden="true" data-abbey="LIKE_COMMENT"></i></button></div><div class="pn-msg__content"><div class="pn-msg__message"><span class="pn-msg__author"><a class="" data-test-hint="MessageItemBody-Link-1">Nancy Snow</a></span>Congratulations!</div><div class="pn-msg__footer"><span>1m</span> <span class="pn-likes-count">1 like</span></div></div></div></div><div class="pn-ms-answer"></div></div></div>
                                    </div>
                                    
                                    <div class="message-item-container pn-msg">
                                        <div class="pn-ms-comment  "><div class="pn-msg-right-side"><div class="pn-msg-top-side"><span class="pn-msg-list-avatar"><span class="pn-msg-avatar">LM</span></span><div class="pn-msg__main"><div class="pn-msg-list-arrow"></div><div class="pn-msg-custom-actions"><button data-abbey="LIKE_COMMENT" class="png-msg__add-remove-action" title="Like" data-test-hint="MessageItemCustomActions-button-2"><i data-abbey="LIKE_COMMENT" class="fa fa-heart-o pn-heart-icon" aria-hidden="true"></i></button></div><div class="pn-msg__content"><div class="pn-msg__message"><span class="pn-msg__author"><a class="" data-test-hint="MessageItemBody-Link-1">Larissa M</a></span>Hi from New Jersey </div><div class="pn-msg__footer"><span>1m</span> <span class="pn-likes-count">1 like</span></div></div></div></div><div class="pn-ms-answer"></div></div></div>
                                    </div>
                                    
                                    <div class="message-item-container pn-msg">
                                        <div class="pn-ms-comment  "><div class="pn-msg-right-side"><div class="pn-msg-top-side"><span class="pn-msg-list-avatar"><span class="pn-msg-avatar">LT</span></span><div class="pn-msg__main"><div class="pn-msg-list-arrow"></div><div class="pn-msg-custom-actions"><button data-abbey="LIKE_COMMENT" class="png-msg__add-remove-action" title="Like" data-test-hint="MessageItemCustomActions-button-2"><i data-abbey="LIKE_COMMENT" class="fa fa-heart-o pn-heart-icon" aria-hidden="true"></i></button></div><div class="pn-msg__content"><div class="pn-msg__message"><span class="pn-msg__author"><a class="" data-test-hint="MessageItemBody-Link-1">Laura T</a></span>Loved Enough Already!</div><div class="pn-msg__footer"><span>1m</span> <span class="pn-likes-count">1 like</span></div></div></div></div><div class="pn-ms-answer"></div></div></div>
                                    </div>
                                    
                                    <div class="message-item-container pn-msg">
                                        <div class="pn-ms-comment  "><div class="pn-msg-right-side"><div class="pn-msg-top-side"><span class="pn-msg-list-avatar"><span class="pn-msg-avatar">LG</span></span><div class="pn-msg__main pn-msg__is-question"><div class="pn-msg-list-arrow"></div><div class="pn-msg-custom-actions"><button class="png-msg__add-remove-action" title="Like" data-test-hint="MessageItemCustomActions-button-2" data-abbey="LIKE_COMMENT"><i class="fa fa-heart-o pn-heart-icon" aria-hidden="true" data-abbey="LIKE_COMMENT"></i></button></div><div class="pn-msg__content"><div class="pn-msg__message"><span class="pn-msg__question">?</span><span class="pn-msg__author"><a class="" data-test-hint="MessageItemBody-Link-1">Larry G</a></span>구입 가능한가요???</div><div class="pn-msg__footer"><span>1m</span> <span class="pn-likes-count">1 like</span></div></div></div></div><div class="pn-ms-answer"></div></div></div>
                                    </div>
                                    
                                    <div class="message-item-container pn-msg">
                                        <div class="pn-ms-comment  "><div class="pn-msg-right-side"><div class="pn-msg-top-side"><span class="pn-msg-list-avatar"><img class="pn-msg-avatar-image" alt="profile-pic-RS" src="https://graph.facebook.com/v15.0/7251107741579210/picture?height=100&amp;width=100" data-test-hint="MessageItem-img-1"></span><div class="pn-msg__main"><div class="pn-msg-list-arrow"></div><div class="pn-msg-custom-actions"><button data-abbey="LIKE_COMMENT" class="png-msg__add-remove-action" title="Like" data-test-hint="MessageItemCustomActions-button-2"><i data-abbey="LIKE_COMMENT" class="fa fa-heart-o pn-heart-icon" aria-hidden="true"></i></button></div><div class="pn-msg__content"><div class="pn-msg__message"><span class="pn-msg__author"><a class="" data-test-hint="MessageItemBody-Link-1">Russ S</a></span>Hi Valerie.</div><div class="pn-msg__footer"><span>1m</span> <span class="pn-likes-count">1 like</span></div></div></div></div><div class="pn-ms-answer"></div></div></div>
                                    </div>
                                    
                                    <div class="message-item-container pn-msg">
                                        <div class="pn-ms-comment  "><div class="pn-msg-right-side"><div class="pn-msg-top-side"><span class="pn-msg-list-avatar"><span class="pn-msg-avatar">CL</span></span><div class="pn-msg__main"><div class="pn-msg-list-arrow"></div><div class="pn-msg-custom-actions"><button class="png-msg__add-remove-action" title="Like" data-test-hint="MessageItemCustomActions-button-2" data-abbey="LIKE_COMMENT"><i class="fa fa-heart-o pn-heart-icon" aria-hidden="true" data-abbey="LIKE_COMMENT"></i></button></div><div class="pn-msg__content"><div class="pn-msg__message"><span class="pn-msg__author"><a class="" data-test-hint="MessageItemBody-Link-1">Cheryl L</a></span>Hello, from Wisconsin!</div><div class="pn-msg__footer"><span>1s</span> <span class="pn-likes-count">1 like</span></div></div></div></div><div class="pn-ms-answer"></div></div></div>
                                    </div>
                                    
                                    <div class="message-item-container pn-msg">
                                        <div class="pn-ms-comment  "><div class="pn-msg-right-side"><div class="pn-msg-top-side"><span class="pn-msg-list-avatar"><img class="pn-msg-avatar-image" alt="profile-pic-HR" src="https://cdn.talkshop.live/eyJidWNrZXQiOiJ0c2wtaW1hZ2VzLXByb2R1Y3Rpb24iLCJrZXkiOiJhdmF0YXJzLzI5NjI0L29yaWdpbmFsL0lNR18yMDIwMDIwNF8xNDA4NDYuanBnIiwiZWRpdHMiOnsicmVzaXplIjp7IndpZHRoIjoxMDAsImhlaWdodCI6MTAwLCJmaXQiOiJmaWxsIn19fQ==" data-test-hint="MessageItem-img-1"></span><div class="pn-msg__main pn-msg__main__no-likes"><div class="pn-msg-list-arrow"></div><div class="pn-msg-custom-actions"><button data-abbey="LIKE_COMMENT" class="png-msg__add-remove-action" title="Like" data-test-hint="MessageItemCustomActions-button-2"><i data-abbey="LIKE_COMMENT" class="fa fa-heart-o pn-heart-icon__inactive" aria-hidden="true"></i></button></div><div class="pn-msg__content"><div class="pn-msg__message"><span class="pn-msg__author"><a class="" data-test-hint="MessageItemBody-Link-1">Henrietta R</a></span>네 그렇습니다. 좋은 하루되세요</div><div class="pn-msg__footer"><span>1s</span> </div></div></div></div><div class="pn-ms-answer"></div></div>
                                        </div>
                                    </div>
                                    
                                    <div class="message-item-container pn-msg">
                                        <div class="pn-ms-comment  "><div class="pn-msg-right-side"><div class="pn-msg-top-side"><span class="pn-msg-list-avatar"><span class="pn-msg-avatar">EM</span></span><div class="pn-msg__main pn-msg__main__no-likes"><div class="pn-msg-list-arrow"></div><div class="pn-msg-custom-actions"><button class="png-msg__add-remove-action" title="Like" data-test-hint="MessageItemCustomActions-button-2" data-abbey="LIKE_COMMENT"><i class="fa fa-heart-o pn-heart-icon__inactive" aria-hidden="true" data-abbey="LIKE_COMMENT"></i></button></div><div class="pn-msg__content"><div class="pn-msg__message"><span class="pn-msg__author"><a class="" data-test-hint="MessageItemBody-Link-1">Emilii M</a></span>Hi - from Texas</div><div class="pn-msg__footer"><span>1s</span> </div></div></div></div><div class="pn-ms-answer"></div></div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                                
                            <div class="png-msg-input">
                                <div class="_1qnsp" data-test-hint="CommentForm-div-1">
                                    <form class="_3dDOy" data-test-hint="CommentForm-form-1">
                                        <div class="_1fGHf">
                                            <div class="_1TW9y _1U0Sp">
                                                <span class="_1l4EX _34giW">pk</span>
                                            </div>
                                        </div>
                                        <div class="_28H0K">
                                            <div class="TJWIi">
                                                <div class="LuNR9">park k</div>
                                                <div>
                                                    <a class="ico_chat inert" role="button" data-abbey="OPEN_GIPHY" data-test-hint="CommentForm-a-1">
                                                        <i class="fa-regular fa-gif" data-abbey="OPEN_GIPHY" aria-hidden="true"></i>
                                                    </a>
                                                    <a class="ico_chat" role="button" data-test-hint="CommentForm-a-2">
                                                        <i class="fa fa-paper-plane" aria-hidden="true"></i>
                                                    </a>
                                                </div>
                                            </div>
                                            <div class="_1AdMv">
                                                <textarea id="commentForm" rows="1" class="FWVFn" placeholder="Say something..." maxlength="200" data-abbey="FOCUS_INPUT_COMMENT" data-test-hint="CommentForm-textarea-1" style="overflow-x: hidden; overflow-wrap: break-word; height: 18px;">
                                                </textarea>
                                                <div class="Nvopg">0/200</div>
                                            </div>
                                        </div>
                                    </form>
                                </div>
                            </div>
                            <div id="chat-notifications">
                                <div class="notifications-wrapper">

                                    <div class="notifications-bc" style="font-family: inherit; position: fixed; width: 320px; padding: 0px 10px 10px; z-index: 9998; box-sizing: border-box; height: auto; top: auto; bottom: 0px; margin: 0px auto 0px -160px; left: 50%;"><div class="notification notification-warning notification-visible" style="position: relative; width: 100%; cursor: pointer; border-radius: 2px; font-size: 13px; margin: 10px 0px 0px; padding: 10px; display: block; box-sizing: border-box; opacity: 1; transition: all 0.3s ease-in-out 0s; transform: translate3d(0px, 0px, 0px); will-change: transform, opacity; border-top: 2px solid rgb(235, 173, 26); background-color: rgb(249, 246, 240); color: rgb(90, 83, 67); box-shadow: rgba(235, 173, 23, 0.9) 0px 0px 1px; bottom: 0px; height: 42px;"><div class="notification-message" style="margin: 0px; padding: 0px;"><div><i class="fa fa-exclamation-triangle" aria-hidden="true"></i> <span>당신의 계정은 차단되었습니다.   <a data-test-hint="Chat-Link-1">Catch up</a></span></div></div><span class="notification-dismiss" style="cursor: pointer; font-family: Arial; font-size: 17px; position: absolute; top: 4px; right: 5px; line-height: 15px; background-color: rgb(225, 207, 172); color: rgb(249, 246, 240); border-radius: 50%; width: 14px; height: 14px; font-weight: bold; text-align: center;">×</span></div></div>

                                </div>
                            </div>
                        </div>
                        <!--Chat End-->
                        <!--제품상세 Start-->
                        <div v-show="currentTab == 1" id="tabpanel-details" role="tabpanel" aria-labelledby="tab-details" class="_2t2Nu tab-content-visible">
                            <div class="_1EbxP">
                                <div class="_27ZJn">
                                    <div class="_3mfWX">
                                        <a name="visit-channel-3" class="KIl-m" data-test-hint="ChannelShowInfo-Link-1" href="/channels/valeriebertinelli">
                                            <div class="_1TW9y _1U0Sp" data-abbey="SELECT_VIEW_CHANNEL_DETAILS">
                                                <img alt="Avatar image" class="_2qclA i0gag" src="https://cdn.talkshop.live/eyJidWNrZXQiOiJ0c2wtaW1hZ2VzLXByb2R1Y3Rpb24iLCJrZXkiOiJ2YXJpYW50X2ltYWdlcy83MzY2NTU0L29yaWdpbmFsL3ZhbGVyaWViZXJ0aW5lbGxpLmpwZWciLCJlZGl0cyI6eyJyZXNpemUiOnsid2lkdGgiOjEwMCwiZml0IjoiY29udGFpbiJ9fX0=" data-abbey="SELECT_VIEW_CHANNEL_DETAILS" data-test-hint="Avatar-img-1">
                                            </div>
                                        </a>
                                        <div class="_1pMMP">
                                            <div class="_2eL4F">
                                                <div class="_39ccA">Indulge - Signed</div>
                                                <div class="_2kFqF">
                                                    by 
                                                    <a name="visit-channel-4" data-abbey="SELECT_VIEW_CHANNEL_DETAILS" data-test-hint="ChannelShowInfo-Link-2" href="/channels/valeriebertinelli">Valerie Bertinelli</a>
                                                </div>
                                            </div>
                                            <div class="_3jwgZ">
                                                <a class="oH6sb _1Vppk" data-abbey="SELECT_UNFOLLOW_CHANNEL_SIDEBAR" data-test-hint="FollowButton-Link-1">
                                                    <span class="wo03T" data-abbey="SELECT_UNFOLLOW_CHANNEL_SIDEBAR">Following</span>
                                                </a>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="_26cGO">
                                    <a name="tag-Harvest" class="_1vh8H" data-test-hint="StreamView-Link-7" href="/watch/eQf-OF9sCnOT?query=Harvest">#Harvest</a>
                                    <a name="tag-cookbook" class="_1vh8H" data-test-hint="StreamView-Link-7" href="/watch/eQf-OF9sCnOT?query=cookbook">#cookbook</a>
                                    <a name="tag-books" class="_1vh8H" data-test-hint="StreamView-Link-7" href="/watch/eQf-OF9sCnOT?query=books">#books</a>
                                </div>
                                <div class="_2sB6i">
                                    <span class="_1dyly">상품상세내용</span>
                                </div>
                            </div>
                        </div>
                        <!--제품상세 End-->
                        <div v-show="currentTab == 2" id="tabpanel-buy" role="tabpanel" aria-labelledby="tab-buy" class="_2t2Nu tab-content-visible">
                            <div id="product-options" class="_11VWy">
                                <!--판매자정보 Start-->
                                <div class="_3UjkZ">
                                    <div class="_3PILd">
                                        <div class="_2R_WV">
                                            <div class="_1oA1A">
                                                <div class="_3rzwD">
                                                    <img src="https://cdn.talkshop.live/eyJidWNrZXQiOiJ0c2wtaW1hZ2VzLXByb2R1Y3Rpb24iLCJrZXkiOiJ2YXJpYW50X2ltYWdlcy83MzY2NTU3L29yaWdpbmFsL3ZhbGVyaWViZXJ0aW5lbGxpLWluZHVsZ2Utc2lnbmVkLmpwZWciLCJlZGl0cyI6eyJyZXNpemUiOnsid2lkdGgiOjI0MCwiZml0IjoiY29udGFpbiJ9fX0=" alt="Indulge - Signed" data-test-hint="Content-img-1">
                                                </div>
                                                <div class="x-Gz_">
                                                    <div class="_3INyu">Indulge - Signed</div>
                                                    <div class="_2yhIv">Watch Now</div>
                                                </div>
                                            </div><div class="uL-pL">
                                                <button class="btn _13P6s" disabled="">
                                                    <i class="fa-regular fa-bell-on" aria-hidden="true"></i>
                                                </button>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <!--판매자정보 End-->
                                <!--제품상세 Start-->
                                <!--TITLE--->
                                <div class="_3QODM">
                                    <div class="_6Zxxv">Products</div>
                                    <div class="ntvW0">Products available for purchase</div>
                                </div>
                                <!--상품담기-->
                                <div class="_1vbey undefined">
                                    <div class="_2HWFu">
                                        <div class="_1jswf" id="product-0">
                                            <div class="_3yBkF">
                                                <div class="xnHWU">
                                                    <div class="cCeSV" data-abbey="OPEN_PRODUCT_IMAGE_LIGHTBOX" data-test-hint="Product-div-1">
                                                        <i class="fa-regular fa-magnifying-glass-plus _3RrKD" data-abbey="OPEN_PRODUCT_IMAGE_LIGHTBOX" aria-hidden="true"></i>
                                                        <img src="https://cdn.shopify.com/s/files/1/1492/7716/products/Glamazon_Mystical_Veil-opt_600x.jpg?v=1632133514" alt="Mystical Veil 2-in-1 Face Makeup Primer" data-abbey="OPEN_PRODUCT_IMAGE_LIGHTBOX" data-test-hint="Product-img-1">
                                                    </div>
                                                    <div class="_1KOsk">
                                                        <span class="km6MK">
                                                            Mystical Veil 2-in-1 Face Makeup Primer
                                                        </span>
                                                        <div>
                                                            <span class="_3G5RD">$34.00</span>
                                                            <div class="_2G72l">
                                                                <div class="_2Ye81">
                                                                    Ships 
                                                                    <span>Tuesday</span>
                                                                </div>
                                                                <div class="_1y49h"></div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div class="_1Ng9d">
                                                    <div class="HZf-c">
                                                        <i class="fas fa-minus _2LZFc" data-abbey="CUSTOMIZE_PRODUCT_QUANTITY_DECREASE" data-test-hint="Product-i-1" aria-hidden="true"></i>
                                                        <div class="_2NqUM">1</div>
                                                        <i class="fas fa-plus _22ftm" data-abbey="CUSTOMIZE_PRODUCT_QUANTITY_INCREASE" data-test-hint="Product-i-2" aria-hidden="true"></i>
                                                    </div>
                                                    <button class="_2_NRv" data-abbey-product-key="dkjTBG6U3iNd" data-abbey="SELECT_ADD_TO_CART_STREAM_VIEW" data-test-hint="Product-button-1">
                                                        Add to cart
                                                    </button>
                                                    <a class="_31lRX" data-abbey="SELECT_VIEW_PRODUCT_DETAILS" data-test-hint="Product-Link-2">
                                                        Full details
                                                        <i class="fa-regular fa-chevron-right _2mEq2" data-abbey="SELECT_VIEW_PRODUCT_DETAILS" aria-hidden="true"></i>
                                                    </a>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="_2HWFu">
                                        <div class="_1jswf" id="product-1">
                                            <div class="_3yBkF">
                                                <div class="xnHWU">
                                                    <div class="cCeSV" data-abbey="OPEN_PRODUCT_IMAGE_LIGHTBOX" data-test-hint="Product-div-1">
                                                        <i class="fa-regular fa-magnifying-glass-plus _3RrKD" data-abbey="OPEN_PRODUCT_IMAGE_LIGHTBOX" aria-hidden="true"></i>
                                                        <img src="https://cdn.shopify.com/s/files/1/1492/7716/files/PralineDreamB_A_s-2_600x.jpg?v=1699845571" alt="Color: Praline Dream No. 2" data-abbey="OPEN_PRODUCT_IMAGE_LIGHTBOX" data-test-hint="Product-img-1">
                                                    </div>
                                                    <div class="_1KOsk">
                                                        <span class="km6MK">Second Skin Foundation Stick</span>
                                                        <div>
                                                            <span class="_3G5RD">$46.00</span>
                                                            <div class="_2G72l">
                                                                <div class="_2Ye81">
                                                                    Ships 
                                                                    <span>Tuesday</span>
                                                                </div>
                                                                <div class="_1y49h">
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div class="_1Ng9d">
                                                    <div class="HZf-c">
                                                        <i class="fas fa-minus _2LZFc" data-abbey="CUSTOMIZE_PRODUCT_QUANTITY_DECREASE" data-test-hint="Product-i-1" aria-hidden="true"></i>
                                                        <div class="_2NqUM">1</div>
                                                        <i class="fas fa-plus _22ftm" data-abbey="CUSTOMIZE_PRODUCT_QUANTITY_INCREASE" data-test-hint="Product-i-2" aria-hidden="true"></i>
                                                    </div>
                                                    <button class="_2_NRv" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="SELECT_ADD_TO_CART_STREAM_VIEW" data-test-hint="Product-button-1">
                                                        Add to cart
                                                    </button>
                                                    <a class="_31lRX" data-abbey="SELECT_VIEW_PRODUCT_DETAILS" data-test-hint="Product-Link-2">
                                                        Full details
                                                        <i class="fa-regular fa-chevron-right _2mEq2" data-abbey="SELECT_VIEW_PRODUCT_DETAILS" aria-hidden="true"></i>
                                                    </a>
                                                </div>
                                            </div>
                                            <div class="vfVa7">
                                                <div class="RB9ze">
                                                    <div class="azGzT">
                                                        <div class="_3iHp7">
                                                            <span>Select</span>
                                                            Color
                                                        </div>
                                                        <div class="_2fs8Y">
                                                            <div class="horizontal_scroll pBGVk" data-test-hint="HorizontalScroll-div-1">
                                                                <div class="_3U7GY" id="options-list-opt-Color-0-product-29254">
                                                                    <div id="val-Porcelain-Doll-No.-1-0-opt-Color-0-product-29254" class="_2fo_D" data-abbey-variant-id="138912" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT" data-test-hint="Product-div-2">
                                                                        <span class="_3Foo6" data-abbey-variant-id="138912" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            Porcelain Doll No. 1
                                                                        </span>
                                                                        <span class="_31uyF" data-abbey-variant-id="138912" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            $46.00
                                                                        </span>
                                                                    </div>
                                                                    <div id="val-Praline-Dream-No.-2-0-opt-Color-0-product-29254" class="_2fo_D _2JZWB" data-abbey-variant-id="138913" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT" data-test-hint="Product-div-2">
                                                                        <span class="_3Foo6" data-abbey-variant-id="138913" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            Praline Dream No. 2
                                                                        </span>
                                                                        <span class="_31uyF" data-abbey-variant-id="138913" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            $46.00
                                                                        </span>
                                                                    </div>
                                                                    <div id="val-Tabagian-Beige-No.-3-0-opt-Color-0-product-29254" class="_2fo_D" data-abbey-variant-id="138914" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT" data-test-hint="Product-div-2">
                                                                        <span class="_3Foo6" data-abbey-variant-id="138914" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            Tabagian Beige No. 3
                                                                        </span>
                                                                        <span class="_31uyF" data-abbey-variant-id="138914" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            $46.00
                                                                        </span>
                                                                    </div>
                                                                    <div id="val-Sunkissed-Tan-No.-4-0-opt-Color-0-product-29254" class="_2fo_D" data-abbey-variant-id="138915" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT" data-test-hint="Product-div-2">
                                                                        <span class="_3Foo6" data-abbey-variant-id="138915" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            Sunkissed Tan No. 4
                                                                        </span>
                                                                        <span class="_31uyF" data-abbey-variant-id="138915" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            $46.00
                                                                        </span>
                                                                    </div>
                                                                    <div id="val-Molten-Pecan-No.-5-0-opt-Color-0-product-29254" class="_2fo_D" data-abbey-variant-id="138916" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT" data-test-hint="Product-div-2">
                                                                        <span class="_3Foo6" data-abbey-variant-id="138916" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            Molten Pecan No. 5
                                                                        </span>
                                                                        <span class="_31uyF" data-abbey-variant-id="138916" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            $46.00
                                                                        </span>
                                                                    </div>
                                                                    <div id="val-Sunkissed-Honey-No.-6-0-opt-Color-0-product-29254" class="_2fo_D" data-abbey-variant-id="138917" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT" data-test-hint="Product-div-2">
                                                                        <span class="_3Foo6" data-abbey-variant-id="138917" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            Sunkissed Honey No. 6
                                                                        </span>
                                                                        <span class="_31uyF" data-abbey-variant-id="138917" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            $46.00
                                                                        </span>
                                                                    </div>
                                                                    <div id="val-Golden-Chestnut-No.-7-0-opt-Color-0-product-29254" class="_2fo_D" data-abbey-variant-id="138918" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT" data-test-hint="Product-div-2">
                                                                        <span class="_3Foo6" data-abbey-variant-id="138918" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            Golden Chestnut No. 7
                                                                        </span>
                                                                        <span class="_31uyF" data-abbey-variant-id="138918" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            $46.00
                                                                        </span>
                                                                    </div>
                                                                    <div id="val-Bronze-Sable-No.-8-0-opt-Color-0-product-29254" class="_2fo_D" data-abbey-variant-id="138919" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT" data-test-hint="Product-div-2">
                                                                        <span class="_3Foo6" data-abbey-variant-id="138919" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            Bronze Sable No. 8
                                                                        </span>
                                                                        <span class="_31uyF" data-abbey-variant-id="138919" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            $46.00
                                                                        </span>
                                                                    </div>
                                                                    <div id="val-Deep-Cocoa-No.-9-0-opt-Color-0-product-29254" class="_2fo_D" data-abbey-variant-id="138920" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT" data-test-hint="Product-div-2">
                                                                        <span class="_3Foo6" data-abbey-variant-id="138920" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            Deep Cocoa No. 9
                                                                        </span>
                                                                        <span class="_31uyF" data-abbey-variant-id="138920" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            $46.00
                                                                        </span>
                                                                    </div>
                                                                    <div id="val-Chocolate-Mousse-No.-12-0-opt-Color-0-product-29254" class="_2fo_D" data-abbey-variant-id="138923" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT" data-test-hint="Product-div-2">
                                                                        <span class="_3Foo6" data-abbey-variant-id="138923" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            Chocolate Mousse No. 12
                                                                        </span>
                                                                        <span class="_31uyF" data-abbey-variant-id="138923" data-abbey-product-key="N3kZ7s0obDLc" data-abbey="CUSTOMIZE_PRODUCT">
                                                                            $46.00
                                                                        </span>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="_10pkf">
                                                <div class="_3nSFX">
                                                    <div class="_8sYYH">
                                                        <i class="fa fa-shopping-cart" aria-hidden="true"></i>
                                                        <span class="_3A3gB">
                                                            Color: Praline Dream No. 2
                                                        </span>
                                                    </div>
                                                    <div>
                                                        <div class="_3va9a">
                                                            <button class="scGof" data-abbey="CUSTOMIZE_PRODUCT_QUANTITY_DECREASE" data-test-hint="QuantityPicker-button-1">
                                                                <i class="fa-duotone fa-circle-minus" data-abbey="CUSTOMIZE_PRODUCT_QUANTITY_DECREASE" aria-hidden="true"></i>
                                                            </button>
                                                            <input readonly="" value="1">
                                                            <button class="scGof" data-abbey="CUSTOMIZE_PRODUCT_QUANTITY_INCREASE" data-test-hint="QuantityPicker-button-2">
                                                                <i class="fa-duotone fa-circle-plus" data-abbey="CUSTOMIZE_PRODUCT_QUANTITY_INCREASE" aria-hidden="true"></i>
                                                            </button>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="_2XIlk"></div>
                                </div>
                                <div class="_19PJG">
                                    <a name="checkout" class="btn primary _2lQ41" data-role="checkout-button" data-abbey="INITIATE_CHECKOUT" href="/checkout">
                                        <strong>$35.00 </strong>Checkout
                                    </a>
                                </div>
                                <!--제품상세 End-->
                            </div>
                        </div>
                    </div>
                </div>
            </nav>
        </div>
    </div>
</template>

<script>
export default {
    name: '#tab_live',
    data() {
        return {
            currentTab: 0,
        }
    },
    methods: {
        hideSlider() {
            if (this.$parent.showLeft == 'true') {
                this.$parent.showLeft = 'false';
                this.$parent.hideControl = 'false';
                this.$parent.offSlide = 'true'
            }
        }
    }
}
</script>

<style lang="scss">
  @import "/src/assets/scss/live_menu.scss";
</style>
