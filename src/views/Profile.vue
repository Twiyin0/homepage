<template>
    <div class="profile-page">
        <section class="section-profile-cover section-shaped my-0">
            <div class="shape shape-style-1 shape-primary shape-skew alpha-4">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
        </section>
        <section class="section section-skew">
            <div class="container">
                <card shadow class="card-profile mt--300" no-body>
                    <div class="px-4">
                        <div class="row justify-content-center">
                            <div class="col-lg-3 order-lg-2">
                                <div class="card-profile-image">
                                    <a href="#">
                                        <img v-lazy="'img/logo/head_c.png'" class="rounded-circle">
                                    </a>
                                </div>
                            </div>
                            <div class="col-lg-4 order-lg-3 text-lg-right align-self-lg-center">
                                <div class="card-profile-actions py-4 mt-lg-0">
                                    <a href="https://jq.qq.com/?_wv=1027&k=atbYkwtD"><base-button type="info" size="sm" class="mr-4">进群玩儿~</base-button></a>
                                    <a href="tencent://message/?uin=1204012590&amp;Site=&amp;menu=yes"><base-button type="default" size="sm" class="float-right">聊聊天~</base-button></a>
                                </div>
                            </div>
                            <div class="col-lg-4 order-lg-1">
                                <div class="card-profile-stats d-flex justify-content-center">
                                    <div>
                                        <span class="heading">10</span>
                                        <span class="description">站点</span>
                                    </div>
                                    <div>
                                        <span class="heading">15</span>
                                        <span class="description">博客</span>
                                    </div>
                                    <div>
                                        <span class="heading">你再骂</span>
                                        <span class="description">身高</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="text-center mt-5">
                            <h3 style="background: linear-gradient(to right, rgb(66, 27, 106), rgb(66, 27, 106), rgb(187, 107, 37)); -webkit-background-clip: text;
                            color: transparent;">暮色音铃
                                <span class="font-weight-light">Twiyin0</span>
                            </h3>
                            <div class="h6 font-weight-300" style="color: rgb(63 135 195);"><i class="ni location_pin mr-2"></i>-[-无聊的时候甚至会敲代码-]-</div>
                            <div class="h6 mt-4"><i class="ni business_briefcase-24 mr-2"></i>一个甚么也不会的CV工程师</div>
                            <div><i class="ni education_hat mr-2"></i>--是个废宅大学生--</div>
                        </div>
                        <div class="mt-5 py-5 border-top text-center">
                            <div class="row justify-content-center">
                                <div class="col-lg-9">
                                    <p>我们可能彼此不太了解，但是相遇即是缘分，不妨与我一同畅聊一会，感受彼此的魅力~<br>
                                    没有远大的理想，没有太高的目标，虽不想远离城市的喧嚣，却想要乡村一样清静……<br>
                                    我们彼此对未来都有过焦虑，振不知道以后要做些什么，应该做些什么~<br>
                                    会不会有心灵的依偎，会不会有亲人的陪伴，会不会留下孤单的自己……<br>
                                    也许我们可以不用考虑太多，做好自己。幸福，总会在未来等你！</p>
                                    <img width="320px" style="border-radius:15px" src="https://img.iin0.cn/uploads/2022/63170d855a00e.jpg">
                                    <!--a href="#">Show more</a-->
                                    <p><br>后面不知道写啥了……</p>
                                    <p>要不，下面的内容~由你与我共同补充w</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </card>
            </div>
        </section>
    </div>
</template>
<script>
export default {};
</script>
<style>
</style>
