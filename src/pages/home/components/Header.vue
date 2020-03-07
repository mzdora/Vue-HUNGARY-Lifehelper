<template>
    <div class="header">
        <div class="header-face">
            <div class="iconfont front-icon">&#xe6de;</div>
        </div>
        <div class="header-left">
            <span class="iconfont">&#xe624;</span>
        </div>
        <div class="header-input">
            <span class="iconfont">&#xe632;</span>
            布达佩斯火车站
        </div>
        <div class="header-right">
            <div class="iconfont back-icon">&#xe783;</div>
        </div>
    </div>
</template>

<script>
export default {
    name : 'HomeHeader',
}
</script>

<style lang="stylus" scoped>
    .header
        display: flex
        background: #FFA500
        height: .86rem
        color: #fff
        .header-face
            float: left
            margin-top : .3rem
            margin-left: .1rem
            .front-icon
                margin-top : -.1rem
                font-size: .6rem
        .header-left
            float: left
            margin-top : .3rem
            margin-left: .1rem
        .header-input
            flex: 1
            height: .64rem
            line-height: .64rem
            margin-top: .12rem
            margin-left : .20rem
            background : #fff
            border-radius: .1rem
            color : #ccc
            text-align: center
        .header-right
            width: 1.24rem
            float: right
            margin-top : .2rem
            text-align: center
            .back-icon
                font-size: .6rem
</style>