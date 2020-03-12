<template>
    <div class="icons">
        <div class="icon">
            <div class="icon-img">
                <img class="icon-img-content" src="https://picbed.qunarzz.com/01d2f57f920666364197a850dab859a8.png">
            </div>
            <p class="icon-desc">酒店/民宿</p>
        </div>
                <div class="icon">
            <div class="icon-img">
                <img class="icon-img-content" src="https://picbed.qunarzz.com/83af731055e121a3251690b225327b56.png">
            </div>
            <p class="icon-desc">租车/代驾</p>
        </div>
                <div class="icon">
            <div class="icon-img">
                <img class="icon-img-content" src="https://picbed.qunarzz.com/3a08f360e958ccb2b947049387873ace.png">
            </div>
            <p class="icon-desc">钱包</p>
        </div>
                <div class="icon">
            <div class="icon-img">
                <img class="icon-img-content" src="https://picbed.qunarzz.com/5b6737be49ca243072ca614f07803b83.png">
            </div>
            <p class="icon-desc">余额查询</p>
        </div>
                <div class="icon">
            <div class="icon-img">
                <img class="icon-img-content" src="https://picbed.qunarzz.com/19b4f6d2fabd617789fa5aad65b249da.png">
            </div>
            <p class="icon-desc">白金卡</p>
        </div>
                <div class="icon">
            <div class="icon-img">
                <img class="icon-img-content" src="https://picbed.qunarzz.com/c65b3bb7571a6bd62df669213e44b84d.png">
            </div>
            <p class="icon-desc">著名景点</p>
        </div>
                <div class="icon">
            <div class="icon-img">
                <img class="icon-img-content" src="https://picbed.qunarzz.com/1e107321f5396ea4994cd832232ecf8a.png">
            </div>
            <p class="icon-desc">购物袋</p>
        </div>
                <div class="icon">
            <div class="icon-img">
                <img class="icon-img-content" src="https://picbed.qunarzz.com/25e3b9f17a21a6e0113c57a23ffccde4.png">
            </div>
            <p class="icon-desc">去周边</p>
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
        padding-bottom: 50%
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
                padding: .1rem
                .icon-img-content
                    display: block
                    margin: 0 auto
                    height: 100%
            .icon-desc
                text-align: center
                position: absolute
                left: 0
                right: 0
                botton: 0
                height: .44rem
                line-height: .44rem
                color: #555
</style>