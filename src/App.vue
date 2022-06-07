<template>
  <div id="app">
    <BaseHeader/>
    <BaseMain/>
    <FooterTop/>
    <FooterMid/>
  </div>
</template>

<script>
import BaseHeader from './components/Header/BaseHeader.vue'
import BaseMain from './components/Main/BaseMain.vue'
import FooterTop from './components/Footer/FooterTop.vue'
import FooterMid from './components/Footer/FooterMid.vue'

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMain,
    FooterTop,
    FooterMid,
  }
}
</script>

<style lang="scss">
@import './assets/style/global.scss'
</style>
