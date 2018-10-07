<template>
    <div class="header">
        <div class="header-left">back</div>
        <div class="header-input">content</div>
        <div class="header-right">city</div>
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
  .header
    display: flex
    line-height: .86rem
    background: #00bcd4
    color: #fff
    .header-left
      width: .64rem
      float: left
    .header-right
      width: 1.24rem
      float: right
      text-align: center
      border-radius: .1rem
    .header-input
      flex: 1
      background: #fff
      line-height: .64rem
      height: .64rem
      margin-top: .12rem
      margin-bottom: .12rem
      color: #ccc
</style>
