<template>
  <div class="header">
    <div class="header-left"><span class="iconfont back-icon">&#xe624;</span></div>
    <div class="header-input"><span class="iconfont">&#xe632;</span>输入城市/景点/游玩主题</div>
  </div>
</template>
<script>
export default {
  name: 'HomeHeader'
}
</script>
<style lang="stylus" scoped>
  @import '~styles/varibles.styl';
  .header
    line-height: .86rem
    display: flex
    background: $bgColor
    color:#fff
    .header-left
      width: .64rem
      float: left
      .back-icon
        margin-left .1rem
        text-align: center
        font-size: .4rem
    .header-input
      flex: 1
      height: .64rem
      line-height: .64rem
      background: #fff
      margin-top: .12rem
      margin-left: .2rem
      padding-left: .2rem
      border-radius: .1rem
      color: #ccc
    .header-right
      width: 1.24rem
      float: right
      text-align: center
      .arrow-icon
        font-size: .24rem
</style>
