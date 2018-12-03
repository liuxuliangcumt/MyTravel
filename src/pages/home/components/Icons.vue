<template>
  <div class="icons">
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png"/>
      </div>
      <p class="icon-desc">热门景点</p>
    </div>

    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png"/>
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png"/>
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png"/>
      </div>
      <p class="icon-desc">热门景点</p>
    </div>
    <div class="icon">
      <div class="icon-img">
        <img class="icon-img-content" src="http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png"/>
      </div>
      <p class="icon-desc">热门景点</p>
    </div>


  </div>
</template>

<script>
  export default {
    name: "HomeIcons",
    data() {
      return {}
    }
  }
</script>

<style scoped>
  .icons {
    width: 100%;
    height: 0;
    overflow: hidden;
    padding-bottom: 50%;
    background: antiquewhite;
  }

  .icon {
    position: relative;
    overflow: hidden;
    float: left;
    width: 25%;
    height: 0;
    padding-bottom: 25%;
  }

  .icon-desc {
    position: absolute;
    left: 0;
    right: 0;
    bottom: 0;
    color: black;
    height: 22px;
    line-height: 44px;
    text-align: center;
    opacity: 0.8;
  }

  .icon-img {

    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 22px;
    padding: 5px;
    box-sizing: border-box;
  }

  .icon-img-content {
    display: block;
    margin: 0px auto;
    height: 100%;
  }


</style>
