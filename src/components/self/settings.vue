<template>
    <!--设置 组件-->
    <div class="setting" v-title data-title="微信">
        <header id="wx-header">
            <div class="center">
                <router-link to ="/self" tag="div" class="iconfont icon-return-arrow">
                    <span>我</span>
                </router-link>
                <span>设置</span>
            </div>
        </header>
        <section>
            <div class="weui-cells-a">
                <router-link to="/self/settings/security" class="weui-cell weui-cell_access">
                    <div class="weui-cell__bd">帐号与安全</div>
                    <div class="weui-cell__ft">已保护</div>
                </router-link>
            </div>
            <div class="weui-cells">
                <router-link to="/self/settings/notice" class="weui-cell weui-cell_access">
                    <div class="weui-cell__bd">新消息通知</div>
                    <div class="weui-cell__ft"></div>
                </router-link>
                <router-link to="/self/settings/privacy" class="weui-cell weui-cell_access">
                    <div class="weui-cell__bd">隐私</div>
                    <div class="weui-cell__ft"></div>
                </router-link>
                <router-link to="/self/settings/common" class="weui-cell weui-cell_access">
                    <div class="weui-cell__bd">通用</div>
                    <div class="weui-cell__ft"></div>
                </router-link>
            </div>
            <div class="weui-cells">
                <a class="weui-cell weui-cell_access" href="https://kf.qq.com/touch/product/wechat_app.html?platform=15&amp;scene_id=kf338">
                    <div class="weui-cell__bd">帮助与反馈</div>
                    <div class="weui-cell__ft"></div>
                </a>
                <div class="weui-cell weui-cell_access">
                    <div class="weui-cell__bd">关于微信</div>
                    <div class="weui-cell__ft">版本7.0.13</div>
                </div>
            </div>
           <div class="weui-cells">
               <div class="weui-cell weui-cell_access">
                    <div class="weui-cell__bd">插件</div>
                    <div class="weui-cell__ft"></div>
                </div>
           </div>
           <div class="weui-cell-b">
                    <div class="weui-cell__b">
                       <font color="#FF0000">切换账号</font>
                    </div>
           </div>
           <div class="weui-cell-b">
                    <div class="weui-cell__b">
                       <font color="#FF0000">退出登录</font>
                    </div>
           </div>
            <!-- <div class="weui-btn-area">
                <button class="weui-btn weui-btn_warn" id="exitBtn">退出登录</button>
            </div> -->
        </section>
    </div>
</template>
<script>
    export default {}
</script>
<style>
.weui-cell-b{
   
    background-color: #fff;
    height: 40px;
    font-size: 15px;
    overflow: hidden;
    position: relative;
    text-align: center;
    line-height: 40px;
    margin-top: 1.17647059em;
    
}
</style>