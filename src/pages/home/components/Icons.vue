<template>
    <div class="icons">
        <div class="icon">
            <div class="icon-img">
                <img class="icon-img-content" src="https://picbed.qunarzz.com/01d2f57f920666364197a850dab859a8.png"/>
            </div>
        </div>
        <div class="icon">
            <div class="icon-img">
                <img class="icon-img-content" src="https://picbed.qunarzz.com/83af731055e121a3251690b225327b56.png"/>
            </div>
        </div>
        <div class="icon">
            <div class="icon-img">
                <img class="icon-img-content" src="https://picbed.qunarzz.com/c65b3bb7571a6bd62df669213e44b84d.png"/>
            </div>
        </div>
        <div class="icon">
            <div class="icon-img">
                <img class="icon-img-content" src="https://picbed.qunarzz.com/3a08f360e958ccb2b947049387873ace.png"/>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'HomeIcons'
}
</script>

<style lang="stylus" scoped>
    .icons
        overflow: hidden
        height: 0
        padding-bottom: 25%
        .icon
            position: relative
            overflow: hidden
            width: 25%
            height: 0
            float: left
            padding-bottom: 25%
            .icon-img
                position: absolute
                top: 0
                left: 0
                right: 0
                botton: .44rem
                box-sizing: border-box
                .icon-img-content
                    display: block
                    margin: 0 auto
                    height: 100%
</style>