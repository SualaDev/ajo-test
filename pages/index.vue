<template>
<div class="main-container">
  <NavBar/>
  <div class="container">
  <div class="background-images">
    <div class="phones"></div>
    <div class="store"></div>
  </div>
  <Details/>
  <Cards/>
  <Review/>
</div>
<Footer/>
</div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
<style scoped>
.main-container{
  position: relative;
}
.container{
  max-width: 1440px;
  margin: 0 auto;
}
.phones{
  background-image: url(~assets/images/phone.png);
  position: absolute;
  width: 580.49px;
  height: 701.75px;
  top: 443px;
  left: 0;
  right:0;
  margin: auto;
}
.store{
  background-image: url(~assets/images/stores.png);
  position: absolute;
  width: 535px;
  height: 84px;
  top: 1241px;
  left: 0;
  right: 0;
  margin: auto;
}
</style>
