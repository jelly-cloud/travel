<template>
  <ul class="list">
<<<<<<< HEAD
    <li class="item">A</li>
    <li class="item">A</li>
    <li class="item">A</li>
    <li class="item">A</li>
    <li class="item">A</li>
    <li class="item">A</li>
    <li class="item">A</li>
    <li class="item">A</li>
    <li class="item">A</li>
    <li class="item">A</li>
    <li class="item">A</li>
<<<<<<< HEAD
=======
    <li class="item">A</li>
    <li class="item">A</li>
    <li class="item">A</li>
>>>>>>> city-list
=======
    <li class="item" v-for="(item, key) of cities" :key="key">{{key}}</li>
>>>>>>> city-ajax
  </ul>
</template>

<script>
export default {
  name: 'CityAlphabet',
  props: {
    cities: Object
  }
}
</script>

<style lang="stylus" scoped>
  @import '~styles/varibles.styl'
  .list
    display flex
    flex-direction column
    justify-content center
    position absolute
    top 1.58rem
    right 0
    bottom 0
    width .4rem
    .item
<<<<<<< HEAD
      line-height .44rem
=======
      line-height .4rem
>>>>>>> city-list
      text-align center
      color $bgColor
</style>
