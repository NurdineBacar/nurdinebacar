<template>
  <div class="container-fluid align-items-center" id="banner">
    <div class="position-absolute" id="info-nurdine">
      <span class="text-white">Olá, sou</span>
      <h1 class="display-6 fw-bold text-white"><span class="">Nurdine Aboo Bacar</span></h1>
      <span class="text-secondary fw-semibold">Um Freelancer</span><br />
      <span class="text-secondary">@Desenvolvedor</span>
    </div>
    <img src="../assets/img/avataaars.png" alt="">
  </div>
</template>

<script>
export default {
  name: "banner",
  data() {
    return {
      bg_img: "/img/banner-1.png",
    };
  },
};
</script>

<style scoped>
#banner {
  background: url("../assets/img/banner-4.png") no-repeat;
  background-size: cover;
  height: 100vh;
  margin-top: -94px;
}

#info-nurdine {
    top: 45%;
    left: 7%;
}

img{
  display: none;
}
@media(max-width:440px){
  img{
    display: block;
    width: 260px;
    position: relative;
    left: 55px;
    top: 120px;
  }
}
</style>
