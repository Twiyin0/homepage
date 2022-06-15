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

                        <p class="description">Raw denim you probably haven't heard of them jean shorts
                            Austin. Nesciunt tofu stumptown aliqua, retro synth master cleanse. Mustache
                            cliche tempor, williamsburg carles vegan helvetica. Reprehenderit butcher retro
                            keffiyeh dreamcatcher synth.</p>
                        <p class="description">Raw denim you probably haven't heard of them jean shorts
                            Austin. Nesciunt tofu stumptown aliqua, retro synth master cleanse.</p>
                    </tab-pane>

                    <tab-pane key="tab2">
                        <template slot="title">
                            <i class="ni ni-favourite-28 mr-2"></i>兴趣爱好
                        </template>

                        <p class="description">Cosby sweater eu banh mi, qui irure terry richardson ex
                            squid. Aliquip placeat salvia cillum iphone. Seitan aliquip quis cardigan
                            american apparel, butcher voluptate nisi qui.</p>
                    </tab-pane>

                    <tab-pane key="tab3">
                        <template slot="title">
                            <i class="ni ni-calendar-grid-58 mr-2"></i>时间线
                        </template>

                        <p class="description">Raw denim you probably haven't heard of them jean shorts
                            Austin. Nesciunt tofu stumptown aliqua, retro synth master cleanse. Mustache
                            cliche tempor, williamsburg carles vegan helvetica. Reprehenderit butcher retro
                            keffiyeh dreamcatcher synth.</p>
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
                          width: 90px;
                "><br><strong>技能列表</strong></p>
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
</style>
