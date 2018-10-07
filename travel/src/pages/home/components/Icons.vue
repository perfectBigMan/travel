<template>
    <div class="icons">
      <div class="icon">
        <div class="icon-div">
          <img class="icon-img" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png"/>
        </div>
        <p class="icon-desc">aaa</p>
      </div>
    </div>
</template>
<script>
export default {
  name: 'Icons',
  data () {
    return {
    }
  }
}
</script>

<style lang="stylus" scoped>
  @import '~styles/varibles.styl'
  .icons
    width: 100%
    height: 0
    overflow: hidden
    padding-bottom: 50%
    // background: green
    .icon
      position: relative
      overflow: hidden
      float: left
      width: 25%
      height: 0
      padding-bottom: 25%
      // background: red
      .icon-div
        position: absolute
        top: 0
        left: 0
        right: 0
        bottom: .44rem
        // background: blue
        box-sizing: border-box
        .icon-img
          height: 100%
          display: block
          margin: 0 auto
      .icon-desc
        position: absolute
        left: 0
        right: 0
        bottom: 0
        height: .44rem
        line-height: .44rem
        text-align: center
        color: $darkTextColor
</style>
