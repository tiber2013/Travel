<template>
<div class="header">
  <div class="header-left">
    <span class="iconfont back-icon">&#xe624;</span>
  </div>
  <div class="header-input">
    <span class="iconfont">&#xe632;</span>
    输入城市景点游玩主题
  </div>
  <div class="header-right">
    城市
    <span class="iconfont arrow-icon">&#xe64a;</span>
  </div>
</div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
@import '~styles/varibles.styl'
.header
  display: flex
  line-height: $headerHeight
  background: $bgColor
  color #fff
  .header-left
    width:.64rem
    float: left
    .back-icon
      text-align: center
      margin-left: .2rem
      font-size:.4rem
  .header-input
    flex: 1
    height:.64rem
    line-height:.64rem
    margin-top:.12rem
    margin-left:.2rem
    margin-right:.2rem
    padding-left:1.2rem
    background: #fff
    border-radius: .1rem
    color: #ccc
  .header-right
    width:1.24rem
    float: right
    .arrow-icon
      font-size:.24rem
</style>
