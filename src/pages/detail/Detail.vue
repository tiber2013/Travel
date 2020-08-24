<template>
<div class="detail">
  <detail-banner></detail-banner>
  <detail-header></detail-header>
  <div class="content"></div>
</div>
</template>

<script>
import DetailBanner from './components/Banner2'
import DetailHeader from './components/Header.vue'
export default {
  name: 'Detail',
  components: {
    DetailBanner,
    DetailHeader
  }
}
</script>

<style lang="stylus" scoped>
@import '~styles/varibles.styl'
.content
  height: 50rem
</style>
