<template>
  <div class="comicsBox">
      <div class="comicImage">
          <img :src="comicObject.thumb" alt="">
      </div>
      <p>
          {{comicObject.series}}    
      </p>
  </div>
</template>

<script>
export default {
    name: "Comics",
    props:{
        comicObject: Object,
    },
}
</script>

<style lang="scss">
.comicsBox{
    .comicImage{
        width: 100px;
        height: 100px;
        overflow: hidden;
        img{
            width: 100%;
        }

    }
}

</style>