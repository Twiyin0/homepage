<template>
    <section class="section-hero section-shaped my-0">
        <div class="shape shape-style-1 bg-1">

        </div>
        <!-- 原版的泡泡背景
        <div class="shape shape-style-1 shape-primary">
            <span class="span-150"></span>
            <span class="span-50"></span>
            <span class="span-50"></span>
            <span class="span-75"></span>
            <span class="span-100"></span>
            <span class="span-75"></span>
            <span class="span-50"></span>
            <span class="span-100"></span>
            <span class="span-50"></span>
            <span class="span-100"></span>
        </div>
        -->
        <div class="container shape-container d-flex align-items-center">
            <div class="col px-0">
                <div class="row justify-content-center align-items-center">
                    <div class="col-lg-7 text-center pt-lg">
                        <img src="img/logo/favicon.png" style="width: 200px;" class="img-fluid">
                        <!-- 
                            颜色渐变效果style
                            background: linear-gradient(to right,#ffffff, #b1ca9e, #9bd0f0); -webkit-background-clip: text;color: transparent;
                        -->
                        <p class="description" style="color: white; font-size: 30px">暮 色 音 铃 T w i y i n 0 </p>
                        <p class="description" style="color: white; font-size: 20px">-[-无聊的时候甚至会敲代码-]-</p>
                        <div class="btn-wrapper">
                            <base-button tag="a"
                                         href="https://github.com/Twiyin0/Vue-homePage"
                                         class="mb-3 mb-sm-0"
                                         type="info"
                                         icon="fa fa-code">
                                源码
                            </base-button>
                            <base-button tag="a"
                                         href="https://blog.twiyin0.cn"
                                         class="mb-3 mb-sm-0"
                                         type="white"
                                         >
                                <object width="14px" data="/img/svg/account-filling.svg" type="image/svg+xml"></object>
                                个人博客
                            </base-button>
                        </div>
                    </div>
                </div>
                <div class="row align-items-center justify-content-around stars-and-coded">
                    <div class="col-sm-4">
                        <span class="text-white alpha-7 ml-3">点个star再走罢</span>
                        <a href="https://github.com/Twiyin0" target="_blank" title="Support us on Github">
                            <img src="img/brand/github-white-slim.png" style="height: 22px; margin-top: -3px">
                        </a>
                    </div>
                    <div class="col-sm-4 mt-4 mt-sm-0 text-right">
                        <a href="https://www.creative-tim.com" target="_blank" title="Creative Tim - Premium Bootstrap Themes and Templates">
                            <img src="img/brand/github-white-slim.png" style="height: 22px; margin-top: -3px">
                        </a>
                        <span class="text-white alpha-7">&nbsp;点个star再走罢</span>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {};
</script>
<style>
</style>
