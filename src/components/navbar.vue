<template>
  <nav class="d-flex align-items-center justify-content-between py-4 px-4">
    <a href="#"><img src="../assets/img/Nur.1.png" width="130px" alt="" /></a>
    <ul class="fw-semibold nav-item-1">
      <li><a href="">Sobre</a></li>
      <li><a href="">Serviços</a></li>
      <li><a href="">Habilidades</a></li>
      <li><a href="">Contato</a></li>
    </ul>
    <div class="nav-item-2">
      <button class="btn btn-outline-secondary hamburguer text-white bt-canva" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasScrolling" aria-controls="offcanvasScrolling">
        <i class="fa-solid fa-bars"></i>
        MENU
      </button>
    </div>
    <div class="offcanvas offcanvas-start nav-item-2 bg-dark text-white" data-bs-scroll="true" data-bs-backdrop="false" tabindex="-1" id="offcanvasScrolling" aria-labelledby="offcanvasScrollingLabel">
      <div class="offcanvas-header">
        <h3 class="offcanvas-title display-4 ms-3 fw-bold" id="offcanvasScrollingLabel">
          MENU
        </h3>
        <button
          type="button"
          class="btn-close bg-white"
          data-bs-dismiss="offcanvas"
          aria-label="Fechar"
        ></button>
      </div>
      <div class="offcanvas-body">
        <p><a href="#about">Sobre</a></p>
        <p><a href="#service">Serviços</a></p>
        <p><a href="#skills">Habilidades</a></p>
        <p><a href="#contact">Contato</a></p>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "navbar",
};
</script>

<style scoped>
nav {
  z-index: 1;
}

ul {
  list-style: none;
  display: flex;
  justify-content: space-around;
}

ul li {
  margin: 0 6px;
  padding: 3px 5px;
  position: relative;
}

ul li a {
  text-decoration: none;
  color: white;

  &:hover {
    color: gray;
  }
}

img {
  margin-top: -20px;
}

.nav-item-2 {
  display: none;
}

.bt-canva {
  margin-top: -13px;
}

p a {
  text-decoration: none;
  color: white;
  font-size: 25px;
  font-weight: 600;
  margin-left: 20px;
}

@media (max-width: 420px) {
  .nav-item-1 {
    display: none;
  }
  .nav-item-2 {
    display: grid;
  }
}
</style>
