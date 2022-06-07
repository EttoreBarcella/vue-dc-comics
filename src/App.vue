<template>
  <div id="app">
    <BaseHeader/>
    <BaseMain/>
    <FooterTop/>
  </div>
</template>

<script>
import BaseHeader from './components/Header/BaseHeader.vue'
import BaseMain from './components/Main/BaseMain.vue'
import FooterTop from './components/Footer/FooterTop.vue'

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMain,
    FooterTop,
  }
}
</script>

<style lang="scss">
@import './assets/style/global.scss'
</style>
