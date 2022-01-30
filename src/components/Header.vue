<template>
  <div>
    <div class="header">
      <div class="logo">
          <Logo/>
      </div>
      <div class="nav">
          <Nav/>
      </div>
    </div>
  </div>
</template>

<script>  
import Logo from './Logo.vue'
import Nav from './Nav.vue'


export default {
  name: 'Header',
  components:{
    Logo,
    Nav,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.header{
  width: 100%;
  height: 120px;
  padding:10px;
  display: flex;
  align-content: center;
  justify-content: space-between;

}
.logo{
width: 20%;
display: flex;
justify-content: end;
}
.nav{
width: 80%;
display: flex;
justify-content: center;
margin-top: 40px;
}
</style>
