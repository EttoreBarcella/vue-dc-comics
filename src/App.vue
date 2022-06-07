<template>
  <div id="app">
    <BaseHeader/>
    <BaseMain/>
    <FooterTop/>
    <FooterMid/>
    <FooterBot/>
  </div>
</template>

<script>
import BaseHeader from './components/Header/BaseHeader.vue'
import BaseMain from './components/Main/BaseMain.vue'
import FooterTop from './components/Footer/FooterTop.vue'
import FooterMid from './components/Footer/FooterMid.vue'
import FooterBot from './components/Footer/FooterBot.vue'

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMain,
    FooterTop,
    FooterMid,
    FooterBot,
  }
}
</script>

<style lang="scss">
@import './assets/style/global.scss'
</style>
