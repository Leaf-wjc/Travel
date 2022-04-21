<template>
    <div>
        <home-header></home-header>
    </div>
</template>

<script>
// 导入组件头部
import HomeHeader from './components/Header.vue'
export default {
    name:'Home',
    //声明局部组件
    components:{
        HomeHeader
    }
}
</script>

<style scoped>

</style>