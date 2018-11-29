<template>
  <div class="header">
    <div class="header-left"><span class="iconfont">
      &#xe601;
    </span></div>
    <div class="header-input">
      <span class="iconfont">&#xe611;</span>
      输入城市/游玩主题/景点
    </div>
    <div class="header-right">城市
      <span class="iconfont arrow-icon">&#xe600;</span>
    </div>
  </div>
</template>
<script>
  export default {
    name: "HomeHeader"
  }
</script>

<style scoped lang="stylus">
  @import "~@styles/varibies.styl"

  .header {
    width: 360px
    line-height: 44px
    display: flex;
    background $bgColor;
    color: white;
  }

  .header-left {
    width: 30px;
    float: left;
  }

  .header-input {
    padding-left: 6px;
    flex: 1;
    background: white;
    border-radius: 5px;
    height: 30px;
    line-height: 30px;
    margin-top: 6px;
    text-align: left;
    margin-left: 6px;
    color: gray;
  }

  .header-right {
    float: right;
    width: 74px;
    height: 44px;
    text-align: center;
  }

  .arrow-icon {
    font-size: 12px;
  }


</style>
