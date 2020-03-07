<template>
    <div class="header">
        <div class="header-face">头像</div>
        <div class="header-left">布达佩斯</div>
        <div class="header-input">布达佩斯火车站</div>
        <div class="header-right">城市</div>
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
            margin-top : .3rem
            text-align: center
</style>