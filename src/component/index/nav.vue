<template>
  <section class="nav">
    <ul class="mui-table-view mui-grid-view mui-grid-9">
        <li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
            <router-link to="/news/list">
                <span class="mui-icon mui-icon-extra mui-icon-extra-new"></span>
                <div class="mui-media-body">新闻</div>
            </router-link>
        </li>
        <li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
            <router-link to="/photo/list/0">
                <span class="mui-icon mui-icon-image"></span>
                <div class="mui-media-body">图片分享</div>
                </router-link></li>
        <li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
             <router-link to="/goods/list">
                <span class="mui-icon mui-icon-extra mui-icon-extra-gift"></span>
                <div class="mui-media-body">商品购买</div>
                </router-link></li>
        <li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
            <router-link to="/todayBefore/tb_list">
                <span class="mui-icon mui-icon-search"></span>
                <div class="mui-media-body">歷史今天</div>
            </router-link></li>
        <li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
            <router-link to="/http_demo/http_demo">
                <span class="mui-icon mui-icon-search"></span>
                <div class="mui-media-body">vueHttp</div>
            </router-link></li>
        <li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
            <router-link to="/bazi/bazi_home">
                <span class="mui-icon mui-icon-search"></span>
                <div class="mui-media-body">bz</div>
            </router-link></li>
        <li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
            <router-link to="/">
                <span class="mui-icon mui-icon-phone"></span>
                <div class="mui-media-body">calendar测试</div>
                </router-link></li>
        <li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
            <router-link to="/">
                <span class="mui-icon mui-icon-gear"></span>
                <div class="mui-media-body">设置</div>
                </router-link></li>
        <li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
            <router-link to="/">
                <span class="mui-icon mui-icon-info"></span>
                <div class="mui-media-body">关于我们</div>
                </router-link></li>
    </ul>
  </section>
</template>

<script>
export default {

};
</script>

<style>

</style>
