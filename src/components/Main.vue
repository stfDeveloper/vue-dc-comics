<template>
  <div class="main">
    <div class="jumboTron">
      <!-- qui va il jumbo -->
    </div>
    <div class="comicsSection">
      <div class="currentSeries">
        CURRENT SERIES
      </div>
      <div class="comicsBox">
        <Comics 
        v-for="(element, index) in comicsInfo "
        :key ="index"
        :comic-object="element"/>  
      </div>
      <button>LOAD MORE</button>


    </div>
    <div class="section">
      <div class="merc">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
        <p> DIGITAL COMICS </p>
      </div>
      <div class="merc">
        <img src="../assets/img/buy-comics-merchandise.png" alt="">
        <p>DC MERCHANDISE</p>
      </div>
      <div class="merc">
        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
        <p>SUBSCRIPTION</p>
      </div>
      <div class="merc">
        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
        <p>COMIC SHOP LOCATOR</p>
      </div>
      <div class="merc">
        <img src="../assets/img/buy-dc-power-visa.svg" alt="">
        <p>DC POWER VISA</p>
      </div>
    </div>
  </div>
</template>

<script>
import comicsList from '../data/comicsData'
import Comics from './Comics.vue'


export default {
  name: 'Main',
  components: {
    Comics,
    },
    data(){
      return{
        comicsInfo : comicsList,
      }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.header{
  position: relative;
}
.jumboTron{
  height: 400px;
  background-image: url(../assets/img/jumbotron.jpg);
  background-size: cover; 
  overflow: hidden;
}
.comicsSection{
  width: 100%;
  height: 700px;
  background-color: rgba(0, 0, 0, 0.829);

}
.comicsBox{
  width: 80%;
  height: 100%;
  display: flex;
  margin: auto;
  flex-wrap: wrap;
  justify-content: space-around;
}
.currentSeries{
  position: relative;
  bottom: 20px;
  left: 200px;
  background-color: rgba(0, 0, 255, 0.89);
  width: 220px;
  padding: 10px;
  text-align: center;
  border-radius: 7px;
}
.section{
  width: 100%;
  height: 150px;
  background-color: rgb(97, 97, 218);
  color: white;
  display: flex;
  align-content: center;
  justify-content: center;

}
.merc{
  width: 250px;
  display: flex;
  justify-content: center;
  align-self: center;
}
.merc img{
  width: 70px;
  height: 80px;
}
p{
  align-self: center;
  margin-left: 10px;
  font-size: 10px;
}
</style>
