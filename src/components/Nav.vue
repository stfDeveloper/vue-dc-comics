<template>
  <div>
    <div class="nav">
      <ul>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>Tv</li>
        <li>Games</li>
        <li>Colectibles</li>
        <li>Videos</li>
        <li>Fans</li>
        <li>News</li>
        <li>Shop</li>

      </ul>
    </div>

  </div>
</template>

<script>
export default {
  name: 'Nav',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
ul{
  display: flex;
  flex-direction: row;
  align-items: center;
  list-style: none;

  li{
    margin: 0 5px;
  }
}

</style>
