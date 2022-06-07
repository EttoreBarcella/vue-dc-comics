
<template>
  <main class="main">
    <BaseHero/>
    <BaseCard/> 
  </main>
</template>

<script>
import BaseHero from '../Sections/BaseHero.vue';
import BaseCard from '../Sections/BaseCard.vue';
export default {
    name: 'BaseMain',
    components: { 
      BaseHero, 
      BaseCard
       },
}
</script>

<style lang="scss" scoped>
</style>