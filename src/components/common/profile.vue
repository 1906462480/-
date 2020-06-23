<template>
<!--个人信息组件-->
    <div class="profile" v-title data-title="微信">
        <header id="wx-header">
            <div class="center">
                <router-link to="/self" tag="div" class="iconfont icon-return-arrow">
                    <span>我</span>
                </router-link>
                <span>个人信息</span>
            </div>
        </header>
        <div class="weui-cells-a">
            <div class="weui-cell" id="avatarCell">
                <div class="weui-cell__bd">
                    <p>头像</p>
                </div>
                <div class="weui-cell__ft">
                    <img src="../../assets/images/weixin-tou.png" style="width: 50px;height: 50px;border-radius: 4px;">
                </div>
            </div>
           
             <router-link to="/self/profile" class="weui-cell weui-cell_access">
                <div class="weui-cell__bd">
                    <p>名字</p>
                </div>
                <div class="weui-cell__ft">
                    胡八一
                </div>
            </router-link>

             <router-link to="/self/profile" class="weui-cell weui-cell_access">
                <div class="weui-cell__bd">
                    <p>微信号</p>
                </div>
                <div class="weui-cell__ft">
                   hsy1906462480
                </div>
            </router-link>
            <router-link to="/self/profile/my-qrcode" class="weui-cell weui-cell_access">
                <div class="weui-cell__bd">
                    <p>我的二维码</p>
                </div>
                <div class="weui-cell__ft">
                    <img src="../../assets/images/chat-info-qr.png" style="vertical-align: middle;;width:24px" class="_align-middle">
                </div>
            </router-link>
            <router-link to="/self/profile" class="weui-cell weui-cell_access">
                <div class="weui-cell__bd">
                    <p>更多</p>
                </div>
                <div class="weui-cell__ft">
                </div>
            </router-link>
        </div>
    <div class="weui-cells">
        <router-link to="/self/profile" class="weui-cell weui-cell_access">
                    <div class="weui-cell__bd">我的地址</div>
                    <div class="weui-cell__ft"></div>
        </router-link>
    </div>

    </div>
</template>
<script>
    export default {
        data() {
            return {
                pageName: "个人信息"
            }
        }
    }
</script>