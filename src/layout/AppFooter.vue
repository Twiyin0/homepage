<template>
    <footer class="footer has-cards">
        <!--
        <div class="container container-lg">
            <div class="row">
                <div class="col-md-6 mb-5 mb-md-0">
                    <div class="card card-lift--hover shadow border-0">
                        <router-link to="/landing" title="Landing Page">
                            <img v-lazy="'img/theme/landing.jpg'" class="card-img">
                        </router-link>
                    </div>
                </div>
                <div class="col-md-6 mb-5 mb-lg-0">
                    <div class="card card-lift--hover shadow border-0">
                        <router-link to="/profile" title="Profile Page">
                            <img v-lazy="'img/theme/profile.jpg'" class="card-img">
                        </router-link>
                    </div>
                </div>
            </div>
        </div>
        -->
        <div class="container">
            <div class="row row-grid align-items-center my-md">
                <div class="col-lg-6">
                    <h3 class="text-primary font-weight-light mb-2">感谢您的支持~</h3>
                    <h4 class="mb-0 font-weight-light">本项目是基于Vue Argon设计的个人主页<br>用到的仅仅是它里面的一点点东西<br>如果您想了解更多关于Vue Argon<br>请访问<a href="https://www.creative-tim.com/product/vue-argon-design-system" target="_blank">源项目</a></h4>
                </div>
                <div class="col-lg-6 text-lg-center btn-wrapper">
                    <!--a target="_blank" rel="noopener" href="https://twitter.com/creativetim"
                       class="btn btn-neutral btn-icon-only btn-twitter btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Follow us">
                        <i class="fa fa-twitter"></i>
                    </a-->
                    <a target="_blank" rel="noopener" href="mailto:twiyin0@outlook.com"
                       class="btn btn-neutral btn-icon-only btn-facebook btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Like me with outlook">
                        <i class="ni ni-email-83"></i>
                    </a>
                    <a target="_blank" rel="noopener" href="http://wpa.qq.com/msgrd?v=3&uin=1204012590&site=qq&menu=yes"
                       class="btn btn-neutral btn-icon-only btn-dribbble btn-lg btn-round" data-toggle="tooltip"
                       data-original-title="Link me with QQ">
                        <i class="fa fa-qq"></i>
                    </a>
                    <a target="_blank" rel="noopener" href="https://github.com/Twiyin0"
                       class="btn btn-neutral btn-icon-only btn-github btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Star on Github">
                        <i class="fa fa-github"></i>
                    </a>
                </div>
            </div>
            <hr>
            <div class="row align-items-center justify-content-md-between">
                <div class="col-md-6">
                    <div class="copyright">
                        <p> &copy; {{year}} Created by <a href="https://iin0.cn" target="_blank" rel="noopener">Twiyin0</a>. Built with <a href="https://www.creative-tim.com/product/vue-argon-design-system" target="_blank" rel="noopener">Argon</a></p>
                    </div>
                    <div class="beian">
                        <p>备案号 <a href="https://beian.miit.gov.cn/" target="_blank" rel="noopener">赣ICP备2023000574号-2</a></p>
                    </div>
                </div>
                <div class="col-md-6">
                    <ul class="nav nav-footer justify-content-end">
                        <li class="nav-item">
                            <a href="https://iin0.cn" class="nav-link" target="_blank" rel="noopener">暮色音铃Twiyin0</a>
                        </li>
                        <!--li class="nav-item">
                            <a href="https://www.creative-tim.com/presentation" class="nav-link" target="_blank" rel="noopener">
                                原作者团队</a>
                        </li-->
                        <li class="nav-item">
                            <a href="http://blog.twiyin0.cn" class="nav-link" target="_blank" rel="noopener">博客</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style>
    .col-lg-6 {
        font-family: "Font-ninininglu", sans-serif;
    }
</style>
