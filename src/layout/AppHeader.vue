<template>
    <header class="header-global">
        <base-nav class="navbar-main" transparent type="" effect="light" expand>
            <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
                <img src="img/logo/logo-16x9.png" alt="logo">
            </router-link>

            <div class="row" slot="content-header" slot-scope="{closeMenu}">
                <!--div class="col-6 collapse-brand">
                    <a href="https://demos.creative-tim.com/vue-argon-design-system/documentation/">
                        <img src="img/brand/blue.png">
                    </a>
                </div-->
                <div class="col-6 collapse-close">
                    <close-button @click="closeMenu"></close-button>
                </div>
            </div>

            <ul class="navbar-nav navbar-nav-hover align-items-lg-center">
                <base-dropdown class="nav-item" menu-classes="dropdown-menu-xl">
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="ni ni-ui-04 d-lg-none"></i>
                        <span class="nav-link-inner--text">我的站点</span>
                    </a>
                    <div class="dropdown-menu-inner">
                        <a href="https://blog.twiyin0.cn" target="_blank"
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-primary rounded-circle text-white">
                                <!--i class="ni ni-spaceship"></i-->
                                <img src="img/logo/head_c.png" style="width: 52px">
                            </div>
                            <div class="media-body ml-3">
                                <h6 class="heading text-primary mb-md-1">音铃的博客</h6>
                                <p class="description d-none d-md-inline-block mb-0">这是我的个人博客,记录我的点点滴滴</p>
                            </div>
                        </a>
                        <a href="https://twiyin0.cn" target="_blank"
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-primary rounded-circle text-white">
                                <!--i class="ni ni-spaceship"></i-->
                                <img src="img/icons/logo/icon-72x72.png" style="width: 52px">
                            </div>
                            <div class="media-body ml-3">
                                <h6 class="heading text-primary mb-md-1">个人主页</h6>
                                <p class="description d-none d-md-inline-block mb-0">这是我的一份个人主页</p>
                            </div>
                        </a>
                        <a href="https://music.twiyin0.cn" target="_blank"
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-warning rounded-circle text-white">
                                <!-- i class="ni ni-ui-04"></i -->
                                <svg style="fill:currentColor; color:white;" t="1653403168111" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="2986" width="100px"><path d="M977.92 697.344q-7.168 38.912-27.648 69.632-17.408 26.624-52.224 48.128t-94.208 21.504q-38.912 0-73.728-5.12t-61.44-17.408-43.52-32.256-19.968-48.64 8.192-59.904 33.792-56.832 54.784-41.984 70.144-16.384q64.512 0 112.64 22.528l0-428.032-464.896 67.584 4.096 570.368 0 25.6q0 30.72-12.288 59.904t-34.304 51.712-53.248 35.84-69.12 13.312q-40.96 0-75.776-7.68t-61.44-22.528-43.008-36.864-19.456-50.688 8.192-55.808 34.304-48.64 55.296-36.352 70.144-18.944q28.672-4.096 56.32-0.512t52.224 11.776l0-571.392 646.144-93.184 0 651.264z" p-id="2987"></path></svg>
                            </div>
                            <div class="media-body ml-3">
                                <h5 class="heading text-warning mb-md-1">聚合音乐</h5>
                                <p class="description d-none d-md-inline-block mb-0">一款聚合bilibili、网易云音乐、QQ音乐的音乐网站</p>
                            </div>
                        </a>
                        <a href="https://url.iin0.cn" target="_blank"
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-warning rounded-circle text-white">
                                <!-- i class="ni ni-ui-04"></i -->
                                <object style="fill:currentColor; color:white; width: 70px" data="/img/svg/url.svg" type="image/svg+xml"></object>
                            </div>
                            <div class="media-body ml-3">
                                <h5 class="heading text-warning mb-md-1">短链接</h5>
                                <p class="description d-none d-md-inline-block mb-0">可以把长长的链接缩短哦~</p>
                            </div>
                        </a>
                    </div>
                </base-dropdown>
                <base-dropdown tag="li" class="nav-item">
                    <a slot="title" href="#" class="nav-link" data-toggle="dropdown" role="button">
                        <i class="ni ni-collection d-lg-none"></i>
                        <span class="nav-link-inner--text">友情链接</span>
                    </a>
                    <!--
                    <router-link to="/landing" class="dropdown-item">Landing</router-link>
                    <router-link to="/profile" class="dropdown-item">Profile</router-link>
                    <router-link to="/login" class="dropdown-item">Login</router-link>
                    <router-link to="/register" class="dropdown-item">Register</router-link>
                    -->
                    <div class="dropdown-menu-inner">
                        <a href="https://blog.vlssu.com" target="_blank"
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-warning rounded-circle text-white">
                                <!-- i class="ni ni-ui-04"></i -->
                                <img src="/img/friends/ssss.png" style="width: 54px; border-radius: 50%">
                            </div>
                            <div class="media-body ml-3">
                                <h5 class="heading text-warning mb-md-1">师叔的小窝</h5>
                                <p class="description d-none d-md-inline-block mb-0">vlssu公益服服主的博客</p>
                            </div>
                        </a>
                        <a href="https://www.creative-tim.com/" target="_blank"
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-warning rounded-circle text-white">
                                <!-- i class="ni ni-ui-04"></i -->
                                <img src="/img/brand/favicon.png" style="width: 54px">
                            </div>
                            <div class="media-body ml-3">
                                <h5 class="heading text-warning mb-md-1">Creative-Tim</h5>
                                <p class="description d-none d-md-inline-block mb-0">The Original Organization Of This Page</p>
                            </div>
                        </a>
                        <a href="https://www.womadao.top" target="_blank"
                           class="media d-flex align-items-center">
                            <div class="icon icon-shape bg-gradient-warning rounded-circle text-white">
                                <!-- i class="ni ni-ui-04"></i -->
                                <img src="/img/friends/wmdlogo.png" style="width: 54px">
                            </div>
                            <div class="media-body ml-3">
                                <h5 class="heading text-warning mb-md-1">沃玛岛服务器</h5>
                                <p class="description d-none d-md-inline-block mb-0">喜欢Minecraft的沃沃头集合在一起开心的玩耍~</p>
                            </div>
                        </a>
                    </div>
                </base-dropdown>
            </ul>
            <ul class="navbar-nav align-items-lg-center ml-lg-auto">
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="mailto:twiyin0@outlook.com" target="_blank" rel="noopener"
                       data-toggle="tooltip" title="我的outlook邮箱">
                        <i class="fa fa-mail-forward"></i>
                        <span class="nav-link-inner--text d-lg-none">outlook</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="http://wpa.qq.com/msgrd?v=3&uin=1204012590&site=qq&menu=yes"
                       target="_blank" rel="noopener" data-toggle="tooltip" title="QQ联系嘛~">
                        <i class="fa fa-qq"></i>
                        <span class="nav-link-inner--text d-lg-none">QQ</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://twitter.com/creativetim" target="_blank" rel="noopener"
                       data-toggle="tooltip" title="在Bilibili看看我嘛">
                        <i class="fa fa-tv"></i>
                        <span class="nav-link-inner--text d-lg-none">bilibili</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://github.com/Twiyin0"
                       target="_blank" rel="noopener" data-toggle="tooltip" title="来Github点歌star嘛">
                        <i class="fa fa-github"></i>
                        <span class="nav-link-inner--text d-lg-none">Github</span>
                    </a>
                </li>
                <li class="nav-item d-none d-lg-block ml-lg-4">
                    <a href="https://www.creative-tim.com/product/vue-argon-design-system" target="_blank" rel="noopener"
                       class="btn btn-neutral btn-icon">
                <span class="btn-inner--icon">
                  <i class="fa fa-cloud-download mr-2"></i>
                </span>
                        <span class="nav-link-inner--text">下载此项目</span>
                    </a>
                </li>
            </ul>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
};
</script>
<style>
</style>
