<template>
    <div class="wrapper">
      <swiper :options="swiperOption">
        <swiper-slide v-for="item of swiperList" :key="item.id">
          <img class="swiper-img" :src="item.imgUrl"/>
        </swiper-slide>
        <!-- Optional controls -->
        <div class="swiper-pagination"  slot="pagination"></div>
      </swiper>
    </div>
</template>
<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      swiperOption: {
        pagination: '.swiper-pagination',
        loop: true
      },
      swiperList: [{
        id: '0001',
        imgUrl: 'https://img1.qunarzz.com/vc/f3/ea/ae/095dd61c09f2797ba9147bd03f.jpg'
      }, {
        id: '0001',
        imgUrl: 'https://img1.qunarzz.com/vc/4e/c2/9a/61222b895136533c133ee9e8bc.jpg'
      }]
    }
  }
}
</script>

<style lang="stylus" scoped>
  @import '~styles/varibles.styl'
  .wrapper >>> .swiper-pagination-bullet-active
    background: #fff !important
  .wrapper
    overflow: hidden
    width: 100%
    heigth: 0
    padding-bottom: 31.25%
    // background: #eee
  .swiper-img
    width: 100%
</style>
