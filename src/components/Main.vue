<template>
  <div class="header">
    <div class="mainHeader">
     Content goes here
    </div>
    <div class="section">
      <div class="comic">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
        <p> DIGITAL COMICS </p>
      </div>
      <div class="comic">
        <img src="../assets/img/buy-comics-merchandise.png" alt="">
        <p>DC MERCHANDISE</p>
      </div>
      <div class="comic">
        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
        <p>SUBSCRIPTION</p>
      </div>
      <div class="comic">
        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
        <p>COMIC SHOP LOCATOR</p>
      </div>
      <div class="comic">
        <img src="../assets/img/buy-dc-power-visa.svg" alt="">
        <p>DC POWER VISA</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Main',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.header{
  position: relative;
}
.mainHeader{
width: 100%;
height: 120px;
background-color: rgba(0, 0, 0, 0.87);
color: white;
text-align: center;
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
.comic{
  width: 250px;
  display: flex;
  justify-content: center;
  align-self: center;
}
.comic img{
  width: 70px;
  height: 80px;
}
p{
  align-self: center;
  margin-left: 10px;
  font-size: 10px;
}
</style>
