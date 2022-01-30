<template>
  <div>
    <div class="footer_jumbo">
      <div class="container">
        <div class="card">
          <p>DC COMICS</p>
            <ul>
              <li>Characters</li>
              <li>Comics</li>
              <li>Movies</li>
              <li>TV</li>
              <li>Games</li>
            </ul>
          <p>SHOP</p>
            <ul>
              <li>Shop DC</li>
              <li>Collectibles</li>
            </ul>
        </div>
        <div class="card">
          <p>DC</p>
          <ul>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
          </ul>
        </div>

        <div class="card">
            <p>SITES</p>
            <ul>
              <li>Characters</li>
              <li>Comics</li>
              <li>Movies</li>
              <li>TV</li>
              <li>Games</li>
            </ul>
          </div>
          <div class="logo_background">
            <img src="../assets/img/dc-logo-bg.png" alt="">
          </div>
        </div>
    </div>
    <div class="lowerFooter">
      <div class="left_lowerFooter">
        <button class="footerBtn">SIGN-UP NOW!</button>
      </div>
      <div class="right_lowerFooter">
        <div class="socials">
          <h3 style="color:rgb(0, 89, 255); align-self: center;" >FOLLOW US</h3>
          <div class="social">
          <img src="../assets/img/footer-facebook.png" alt="">
          </div>
          <div class="social">
          <img src="../assets/img/footer-periscope.png" alt="">
          </div>
          <div class="social">
          <img src="../assets/img/footer-pinterest.png" alt="">
          </div>
          <div class="social">
          <img src="../assets/img/footer-twitter.png" alt="">
          </div>
          <div class="social">
          <img src="../assets/img/footer-youtube.png" alt="">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.footer_jumbo{
  display: flex;
  width: 100%;
  color: white;
  height: 300px;
  background-image: url(../assets/img/footer-bg.jpg);
  background-size: cover;
  overflow: hidden;
}
.container{
  display: flex;
  width: 70%;
  height: 100%;
  position: relative;
}
p{
  font-size:19px ;
  margin-top: 10px;
}
li{
  font-size: 22px ;
  color: rgba(255, 255, 255, 0.568);
  list-style: none;
}
.card{
  margin-left: 50px;
  margin-top: 50px;
}
.logo_background img{
width: 600px;
margin-left: 200px;
}
.logo_background{
  position: relative;
top: -100px;
right: -100px;
  img{
    width: 500px;
    height: 500px;
  }
}
.lowerFooter{
  height: 131px;
  width: 100%;
  background-color: rgba(0, 0, 0, 0.753);
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
.right_lowerFooter{
  align-self: center;

}
.left_lowerFooter{
  align-self: center;
}
.footerBtn{
  padding: 10px;
  background-color: transparent;
  border: 2px solid rgb(0, 89, 255);
  color: white;
}
.socials{
  display: flex;
}
.social{
  margin-left: 15px;
}

</style>
