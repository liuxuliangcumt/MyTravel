<script src="../../../main.js"></script>
<template>
  <div class="wrapper">

    <swiper :options="swiperOption" ref="mySwiper">


      <swiper-slide v-for="item of swiperList" :key="item.id">
        <img class="swiper-img" :src="item.url"/>
      </swiper-slide>
      <div class="swiper-pagination" slot="pagination"/>
    </swiper>

  </div>

</template>

<script>
  export default {
    name: "HomeSwiper",
    data() {
      return {
        swiperOption: {
          autoplay: true,
          loop: true,
          pagination: {
            el: '.swiper-pagination',
          }
        },
        swiperList: [{
          id: 1,
          url: "https://img1.qunarzz.com/vc/2f/8e/51/cb4d31b360c836f7d1bbe83c13.jpg"
        }, {
          id: 2,
          url: "https://img1.qunarzz.com/vc/a5/e0/64/c6bd8680fb67247db15df6057b.jpg"
        }, {
          id: 3,
          url: "https://img1.qunarzz.com/vc/a5/e0/64/c6bd8680fb67247db15df6057b.jpg"
        }],
      }
    }
  }
</script>

<style scoped lang="stylus">
  .swiper-img {
    width 100%
  }

  .wrapper {
    width 100%;
    height 0;
    overflow hidden;
    padding-bottom 31.5%
  }
</style>
