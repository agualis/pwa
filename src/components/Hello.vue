<template>
  <div class="hello">
    <h5>Welcome to your my PWA</h5>
    <img src="~assets/bob.jpg" alt="Bob">
    <img src="~assets/enjuto.jpg" alt="Enjuto">
    <img src="~assets/ignatius.jpg" alt="Ignatius">
  </div>
</template>

<script>
export default {
  name: 'hello'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus">
@import '~variables'

.hello
  margin-top 50px
  a
    color #35495E

ul
  list-style-type none
  padding 0

li
  display inline-block
  margin 0 10px
</style>
