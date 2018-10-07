<template>
    <div class="header">
        <div class="header-left"><span class="iconfont back-icon">&#xe624;</span></div>
        <div class="header-input"><span class="iconfont">&#xe632;</span></div>
        <div class="header-right">city<span class="iconfont arrow-icon">&#xe62d;</span></div>
    </div>
</template>
<script>
export default {
  data () {
    return {
    }
  }
}
</script>

<style lang="stylus" scoped>
  @import '~styles/varibles.styl'
  .header
    display: flex
    line-height: .86rem
    background: $bgColor
    color: #fff
    .header-left
      width: .64rem
      float: left
      .back-icon
        text-align: center
        font-size: .4rem
    .header-right
      width: 1.24rem
      float: right
      text-align: center
      border-radius: .1rem
      .arrow-icon
        font-size: .24rem
        padding-left: .1rem
    .header-input
      flex: 1
      background: #fff
      line-height: .64rem
      height: .64rem
      margin-top: .12rem
      margin-bottom: .12rem
      padding-left: .2rem
      color: #ccc
</style>
