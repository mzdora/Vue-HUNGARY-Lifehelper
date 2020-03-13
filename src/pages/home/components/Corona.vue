<template>
    <div>
        <div class="title">疫情防控</div>
        <ul>
            <li class="item border-bottom" v-for="item of recommendList" :key="item.id">
                <div class="item-img-wrapper">
                <img class="item-img" :src="item.imgUrl"/>
                </div>
                <div class="item-info">
                    <p class="item-title">{{item.title}}</p>
                    <p class="item-desc">{{item.desc}}</p>
                </div>
            </li>
        </ul>
    </div>
</template>

<style lang="stylus" scoped>
    .title
        line-height: .6rem
        background: #eee
        text-indent: .2rem
    .item-img-wrapper
        overflow: hidden
        height: 0
        padding-bottom: 50%
        .item-img
            width: 100%
    .item-title
        line-height: .54rem
        font-size: .32rem
    .item-desc
        line-height: .3rem
        color: #ccc
        padding-bottom: .1rem

</style>
<script>
export default {
    name : 'HomeCorona',
    data(){
        return{
            recommendList:[{
                id: '0001',
                imgUrl: 'https://koronavirus.gov.hu/sites/default/files/sites/default/files/imce/hatar.jpg',
                title:'采取特别措施：从午夜开始实施边境管制',
                desc:'冠状病毒Corona现在正式成为全球流行病。政府宣布了紧急状态和紧急措...'
            },
            {
                id: '0002',
                imgUrl: 'https://www.elte.hu/media/e4/52/c2d2d47a27ab38355ed0f73600a41554388a69660f6493ae98c9420068d4/koronavirus-covid-thumb.jpg',
                title:'关于冠状病毒病传播所采取的政府措施的执行',
                desc:'根据政府的决定，2019/2020学年春季学期的春假（修订了学术日...'
            }]
        }
    }
}
</script>