<template>
  <div class="container-fluid bg-white pt-4 pb-4 px-5">
    <div class="row g-1">
      <h2 class="display-6 fw-semibold text-center mb-3">Contato</h2>
      <div class="row text-center mt-3">
        <div class="col-md">
          <label for="" class="align-items-center fw-semibold mb-2">
            <i class="fa-solid fa-phone"></i>
            <span class="ms-2">Ligue para mim</span>
          </label><br />
          <span><a href="tel:+258845636664">(+258) 84 563 6664</a></span><br />
          <span><a href="tel:+258864456239">(+258) 86 445 6239</a></span><br />
        </div>
        <div class="col-md">
          <label for="" class="align-items-center fw-semibold mb-2">
            <i class="fa-brands fa-whatsapp"></i>
            <span class="ms-2">Whatsapp</span>
          </label><br />
          <span><a href="https://api.whatsapp.com/send?phone=258845636664" target="_blank">(+258) 84 563 6664</a></span>
        </div>
        <div class="col-md">
          <label for="" class="align-items-center fw-semibold mb-2">
            <i class="fa-solid fa-envelope"></i>
            <span class="ms-2">Email</span>
          </label><br />
          <span><a href="mailto:nurdinebacar@gmail.com">nurdinebacar@gmail.com</a></span>
        </div>
        <div class="col-md">
          <label for="" class="align-items-center fw-semibold mb-2">
            <i class="fa-solid fa-location"></i>
            <span class="ms-2">Localização</span>
          </label><br />
          <span>Moçambique, Cidade de Maputo</span>
        </div>
      </div>
      <div class="col-md-12 text-center">
        <p class="fw-semibold fs-5">Envie-me uma mensagem</p>
      </div>
      <hr class="w-100 mx-center" />
      <div class="row px-5 text-center">
        <div class="col-md-4 mb-1">
          <a href="#"><img src="../assets/img/Nur.1.png" width="130px" alt="" /></a>
        </div>
        <div class="col-md-4"></div>
        <div class="col-md-4 text-center align-items-center">
          <span class="text-secondary">Todos os direitos reservados - 2024</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "contact",
};
</script>

<style scoped>
span a {
  text-decoration: none;
  color: black;
}
</style>
