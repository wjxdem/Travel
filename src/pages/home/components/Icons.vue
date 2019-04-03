 <template>
  <div class="icons">
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1611/54/ace00878a52d9702.png"/>
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
  </div>
</template>

<script>
export default {
  name:"HomeIcons"
}
</script>

<style lang="stylus" scoped>
  @import '~styles/varibles.styl';
  .icons
    overflow: hidden
    height: 0
    padding-bottom: 50%
    .icon
      position: relative
      overflow: hidden
      width: 25%
      float: left
      padding-bottom: 25%
      .icon-img
        position: absolute
        top: 0
        left: 0
        right: 0
        bottom: 0.44rem
        box-sizing: border-box
        padding:. 1rem
        .icon-img-content
          height: 100%
          display: block
          margin: 0 atuo
      .icon-desc
        position: absolute
        left: 0
        right: 0
        botton: 0
        height: .44rem
        line-height: .44rem
        color: $darkTextColor
        text-align: center
</style>
