<template>
    <div class="wrapper">
        <swiper :options="swiperOption">
            <!-- slides -->
            <swiper-slide>
                <img class="swiper-img" src="https://dshs.texas.gov/uploadedImages/Content/Consumer_and_External_Affairs/coronavirus/banner-interior2.png">
            </swiper-slide>
            <swiper-slide>
                <img class="swiper-img" src="../../../../graphs/hungary.jpg">
            </swiper-slide>
            <swiper-slide>
                <img class="swiper-img" src="../../../../graphs/elte.jpg">
            </swiper-slide>
            <!-- Optional controls -->
            <div class="swiper-pagination"  slot="pagination"></div>
        </swiper>
    </div>
</template>

<script>
export default{
    name: 'HomeSwiper',
    data: function(){
        return {
            swiperOption: {
                pagination: '.swiper-pagination'
            }
        }
    }
}
</script>

<style lang="stylus" scoped>
    .wrapper >>> .swiper-pagination-bullet-active
        background: #FFA500
    .wrapper .swiper-img
        width: 100%
</style>