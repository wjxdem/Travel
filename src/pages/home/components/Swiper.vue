<template>
  <div class="warpper">
    <swiper :options="swiperOption">
    <swiper-slide v-for="item of swiperList" :key="item.id">
      <img class="swiper-img" :src="item.imgUrl" />
    </swiper-slide>
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
        id: '00001',
        imgUrl: require('@/assets/images/db.jpg')
      },
      {
        id: '00002',
        imgUrl: require('@/assets/images/4d.jpg')
      }]
    }
  }
}
</script>
<style lang="stylus" scoped>
.warpper >>> .swiper-pagination-bullet-active {
  background: #fff;
}
.warpper
  width: 100%
  height: 0
  overflow hidden
  padding-bottom:46%
  .swiper-img
    width: 100%
</style>
