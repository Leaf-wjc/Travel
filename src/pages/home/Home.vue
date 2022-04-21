<template>
    <div>
        <home-header></home-header>
        <home-swiper></home-swiper>
    </div>
</template>

<script>
// 导入组件头部
import HomeHeader from './components/Header.vue'
import HomeSwiper from './components/Swiper.vue'
export default {
    name:'Home',
    //声明局部组件
    components:{
        HomeHeader,
        HomeSwiper
    }
}
</script>

<style scoped>

</style>