<template>
    <section class="headbar row" v-show="!hideHeadbar">
        <div class="col"><i class="logo"></i></div>
        <i class="icon-service"></i>
        <a href="javascript:;" class="online-service" data-track="index_webCustomerSevice_new">在线客服</a>
    </section>
</template>
<script>
export default {
    data() {
        return {
            hideHeadbar: false
        }
    },
    mounted() {
        let userAgent = navigator.userAgent.toLowerCase()
        if( userAgent.indexOf('mucxiaoyusan') > 0 ){
            this.hideHeadbar = true;        
        }
    }
}
</script>
<style lang="scss">
    @import '@/assets/css/index/head.scss';
</style>


