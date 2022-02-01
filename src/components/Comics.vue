<template>
  <div class="comic">
    <img :src="comicObject.thumb" alt="">
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
.comic{
    width: 150px;
    height: 200px;
    img{
        width: 150px;
    }
    p{
        text-align: center;
    }
}

</style>