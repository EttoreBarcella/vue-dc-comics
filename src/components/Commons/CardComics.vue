<template>
  <div class="card">
      <div class="image_box">
          <img :src="image" :alt="title">
      </div>
    <h3>{{title}}</h3>
  </div>
</template>

<script>
export default {
name: "CardComics",
 props: {
        title: String,
        image: String,
    }
}
</script>

<style lang="scss" scoped>
.image_box{
    height: 200px;
    
}
img{
    width: 100%;
    height: 100%;
    object-position: top;
  
}
</style>