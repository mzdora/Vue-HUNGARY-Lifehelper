<template>
    <div>
        <home-header></home-header>
        <home-swiper></home-swiper>
        <home-icons></home-icons>
        <home-corona></home-corona>
        <home-recommend></home-recommend>
    </div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeSwiper from './components/Swiper'
import HomeIcons from './components/Icons'
import HomeRecommend from './components/Recommend'
import HomeCorona from './components/Corona'
export default {
    name : 'Home',
    components : {
        HomeHeader,
        HomeSwiper,
        HomeIcons,
        HomeRecommend,
        HomeCorona
    }
}
</script>

<style>
</style>