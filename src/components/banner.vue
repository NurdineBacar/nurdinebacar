<template>
  <div class="container-fluid align-items-center" id="banner">
    <div class="position-absolute" id="info-nurdine">
      <span class="text-white">Olá, </span>
      <h1 class="display-6 fw-bold text-white">Sou <span class="">Nurdine Aboo Bacar</span></h1>
      <span class="text-secondary fw-semibold">Freelancer Web Designer</span><br />
      <span class="text-secondary">@Desenvolvedor</span>
    </div>
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
  /* background: url("/img/banner-3.png") no-repeat; */
  background: url("../img/banner-3.png") no-repeat;
  background-size: cover;
  height: 100vh;
  margin-top: -94px;
}

#info-nurdine {
    top: 45%;
    left: 7%;
}
</style>
