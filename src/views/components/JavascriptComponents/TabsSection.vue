<template>
    <div class="row justify-content-center">
        <div class="col-lg-6">
            <!-- Tabs with icons 
            <div class="mb-3">
                <small class="text-uppercase font-weight-bold">With icons</small>
            </div>-->
            <tabs fill class="flex-column flex-md-row">
                <!-- old {activeTabIndex}未使用问题
                <card shadow slot-scope="{activeTabIndex}">
                -->
                <card shadow slot-scope="">
                    <tab-pane key="tab1">
                        <template slot="title">
                            <i class="ni ni-satisfied mr-2"></i>个人介绍
                        </template>
                        <badge type="info" class="text-uppercase">御宅</badge>
                        <badge type="primary" class="text-uppercase">ACG</badge>
                        <badge type="warning" class="text-uppercase">大概是攻吧</badge>
                        <badge type="success" class="text-uppercase">总之就是非常草</badge>
                        <p class="description">
                            暮色音铃，英文名Twiyin0(Twilight Yinling)。<br>
                            圈名来源MC暮色森林和最喜欢的汉字和数字，即音-零,因此简写Twi-yin0。
                            受网络冲击中华汉字文化的影响，将零改为铃，但英文名还是以零为译。
                            </p>
                        <p class="description">
                            如你所见，是歌随处可见的大学生，平时没什么事做就打打游戏，无聊甚至会敲代码。
                            ACG狂热爱好者，每次新番更新都会去看看，喜欢\芳文社/。<br>
                            大二学生，电子信息工程专业，前端是爱好，主要想专业学习嵌入式和物联网。
                            社恐，不太会说话，但我很乐意跟别人在QQ或微信聊天。
                            </p>
                    </tab-pane>

                    <tab-pane key="tab2">
                        <template slot="title">
                            <i class="ni ni-favourite-28 mr-2"></i>兴趣爱好
                        </template>
                        <badge type="primary" class="text-uppercase">ACG</badge>
                        <badge type="warning" class="text-uppercase">荤素均衡</badge>
                        <badge type="primary" class="text-uppercase">治愈音乐</badge>
                        <p class="description">
                            喜欢ACG，也就是二次元，15年入宅。近期在看间谍过家家，RPG不动产和勇者辞职不干了。
                            最喜欢的是\芳文社/。轻音最棒辣！！治愈倾向(真的不是致郁哦)，可可爱爱的番最治愈了
                            喜欢吃辣，似fulan银。不挑食，但吃太油腻的食物会反胃，最喜欢的蔬菜是苦瓜=w=
                        </p>
                        <p class="description">
                            不太喜欢运动，不是呆在家就是呆宿舍，不怎么出门。
                            最喜欢的游戏是《刺客信条》系列，目前在玩奥德赛二周目。Minecraft是陪伴我五年的游戏。上班游戏喜欢原神，养老婆=w=
                            喜欢听治愈系风格的音乐，纯音乐喜欢催眠向，因为我睡眠质量不太行=w=好像就这么多了罢.....
                        </p>
                    </tab-pane>

                    <tab-pane key="tab3">
                        <template slot="title">
                            <i class="ni ni-calendar-grid-58 mr-2"></i>时间线
                        </template>

                        <p class="description">
                            [2019] 启蒙<br>
                            与橙息一起创办"warma鸡窝服务器"，也是我学代码的启蒙之时。<br>
                            [2020-2021] 启程<br>
                            20年刚好上大学，与橙息、水灵等人创办沃玛岛。遇到师叔开始我的前端之旅.......<br>
                            [2021 夏] 初学<br>
                            在师叔的帮助下，搭建了我的第一个个人博客，开始坠入深渊（bushi）<br>
                            [2021 冬至今] 初探<br>
                            慢慢开始在学前端的路上走，有的时候甚至忘了自己究竟是学啥的了.....<br>
                        </p>
                        <p class="description">
                            [Future] 未来<br>
                            不知道今后的路怎么走，现在还挺迷茫的，有人说我前途一片光明，但我内心却是如此荒芜....
                        </p>
                    </tab-pane>
                </card>
            </tabs>
        </div>

        <!-- 进度条样式 -->
        <div class="col-lg-5">
                <p style="font-size: 20px;
                          background: linear-gradient(to right, #32bf, #3e15);
                          -webkit-background-clip: text;
                          color: transparent;
                          width: 120px;
                "><br><strong style="font-size: 30px;">技能列表</strong></p>
                <base-progress type="info" :value="95" label="摆烂" v-b-tooltip.hover.top title="总之就是摆！"></base-progress>
                <base-progress type="primary" :value="50" label="C/C++" v-b-tooltip.hover.top title="专业所需"></base-progress>
                <base-progress type="warning" :value="25" label="前端" v-b-tooltip.hover.top title="兴趣爱好"></base-progress>
        </div>

        <!--
        <div class="col-lg-6 mt-5 mt-lg-0">
             Menu 
            <div class="mb-3">
                <small class="text-uppercase font-weight-bold">With text</small>
            </div>
            <tabs fill class="flex-column flex-md-row">
                <card shadow>
                    <tab-pane title="Home">
                        <p class="description">Raw denim you probably haven't heard of them jean shorts
                            Austin. Nesciunt tofu stumptown aliqua, retro synth master cleanse. Mustache
                            cliche tempor, williamsburg carles vegan helvetica. Reprehenderit butcher retro
                            keffiyeh dreamcatcher synth.</p>
                        <p class="description">Raw denim you probably haven't heard of them jean shorts
                            Austin. Nesciunt tofu stumptown aliqua, retro synth master cleanse.</p>
                    </tab-pane>

                    <tab-pane title="Profile">
                        <p class="description">Cosby sweater eu banh mi, qui irure terry richardson ex
                            squid. Aliquip placeat salvia cillum iphone. Seitan aliquip quis cardigan
                            american apparel, butcher voluptate nisi qui.</p>
                    </tab-pane>

                    <tab-pane title="Messages">
                        <p class="description">Raw denim you probably haven't heard of them jean shorts
                            Austin. Nesciunt tofu stumptown aliqua, retro synth master cleanse. Mustache
                            cliche tempor, williamsburg carles vegan helvetica. Reprehenderit butcher retro
                            keffiyeh dreamcatcher synth.</p>
                    </tab-pane>
                </card>
            </tabs>
            
        </div>
        -->
    </div>
</template>
<script>
import Tabs from "@/components/Tabs/Tabs.vue";
import TabPane from "@/components/Tabs/TabPane.vue";
export default {
  components: {
    Tabs,
    TabPane
  }
};
</script>
<style>
    .col-lg-5 {
        font-family: "Font-ninininglu", sans-serif;
    }
</style>
