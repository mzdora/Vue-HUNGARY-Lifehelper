<template>
    <div>
        <home-header></home-header>
        <home-swiper></home-swiper>
        <div>接下来是实现标签栏</div>
    </div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeSwiper from './components/Swiper'
export default {
    name : 'Home',
    components : {
        HomeHeader,
        HomeSwiper
    }
}
</script>

<style>
</style>