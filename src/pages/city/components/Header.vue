<template>
  <div class="header">
    城市选择
    <router-link to="/">
      <div class="iconfont head-back">&#xe624;</div>
    </router-link>

  </div>
</template>

<script>
export default {
  name: 'CityHeader'
}
</script>

<style scoped lang="stylus">

  @import "~styles/varibles.styl"
.header
  position relative
  overflow: hidden
  height: $headerHeight
  line-height $headerHeight
  text-align center
  color #ffffff
  background $bgColor
  font-size .32rem
  .head-back
    position absolute
    top: 0
    left: 0
    width .64rem
    text-align center
    font-size .4rem
    color #fff
</style>
