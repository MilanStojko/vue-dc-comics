<template>
    <div>
    <FooterTop/>
    <FooterMain/>
    <FooterInfo/>
    </div>
</template>

<script>
import FooterTop from './FooterTop.vue';
import FooterMain from './FooterMain.vue';
import FooterInfo from './FooterInfo.vue';

export default {
    name:'Footer',
    components:{
        FooterTop,
        FooterMain,
        FooterInfo
    }
};
</script>

<style lang="scss" scoped>
</style>