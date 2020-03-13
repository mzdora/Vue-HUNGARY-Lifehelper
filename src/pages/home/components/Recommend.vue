<template>
    <div>
        <div class="title">景点推荐</div>
        <ul>
            <li class="item border-bottom" v-for="item of recommendList" :key="item.id">
                <img class="item-img" :src="item.imgUrl"/>
                <div class="item-info">
                    <p class="item-title">{{item.title}}</p>
                    <p class="item-desc">{{item.desc}}</p>
                    <button class="item-button">查看详情</button>
                </div>
            </li>
        </ul>
    </div>
</template>

<style lang="stylus" scoped>
    .title
        line-height: .6rem
        background: #ccc
        text-indent: .2rem
    .item
        overflow:hidden
        display: flex
        height: 1.9rem
        .item-img
            width:1.7rem
            height: 1.7rem
            padding: .1rem
        .item-info
            flex: 1
            padding: .1rem
            .item-title
                line-height: .54rem
                font-size: .32rem
            .item-desc
                line-height: .4rem
                color: #ccc
            .item-button
                line-height: .44rem
                margin-top: .16rem
                background: #ff9300
                padding: 0 .2rem
                border-radius: .06rem
                color: #fff

</style>

<script>
export default {
    name : 'HomeRecommend',
    data(){
        return{
            recommendList:[{
                id: '0001',
                imgUrl: 'https://youimg1.c-ctrip.com/target/10080m000000dfppd2957_D_800_600.jpg',
                title:'渔人堡',
                desc:'欣赏多瑙河的壮美景色'
            },
            {
                id: '0002',
                imgUrl: 'https://youimg1.c-ctrip.com/target/100f0n000000dzs550163_D_800_600.jpg',
                title:'国会大厦',
                desc:'欧洲最古老的立法机构之一'
            },{
                id: '0003',
                imgUrl: 'https://dimg07.c-ctrip.com/images/fd/tg/g2/M00/8D/92/Cghzf1WxAjyAM8WRABguv0h9swo267_C_300_256_Q80.jpg',
                title:'英雄广场',
                desc:'美术和艺术的完美结合'
            },{
                id: '0004',
                imgUrl: 'data:image/jpeg;base64,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',
                title:'罗兰大学',
                desc:'匈牙利最棒的计算机类大学'

            }]
        }
    }
}
</script>