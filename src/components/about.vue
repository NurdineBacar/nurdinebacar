<template>
  <div class="container-fluid bg-dark pt-4 pb-3 px-5">
    <div class="row g-1 text-white">
      <h2 class="display-6 fw-semibold text-center mb-3" id="about">Sobre</h2>
      <div class="col-md-5">
        <img src="../assets/img/profile.png" class="rounded-circle" alt="Imagem de Nurdine" />
      </div>
      <div class="col-md me-3">
        <div class="row fs-6">
          <div class="col-md-12 mb-3">
            <p>
              Olá! Sou Nurdine Aboo Bacar, um entusiasta do desenvolvimento de sistemas. Com habilidades notáveis em algumas linguagens web e desktop, como HTML, CSS e Java. Estou constantemente explorando novas técnicas e tendências para aprimorar minhas habilidades.

              Estou sempre pronto para enfrentar desafios e mergulhar em novos projetos, encontrando soluções criativas para problemas complexos. Acredito que aprender é uma jornada contínua e estou sempre buscando expandir meus horizontes e melhorar.

              Tenho uma personalidade descontraída e adoro compartilhar risadas com meus colegas enquanto trabalhamos juntos em projetos empolgantes. Estou sempre aberto a novas oportunidades de colaboração e espero fazer parte de equipes dinâmicas e inovadoras.
            </p>
          </div>
          <div class="col-md-6 text-center mb-3">
            <span class="fw-semibold text-center text-secondary details-nurdine">Nome</span> <br />
            <span class="text-center">Nurdine Aboo Bacar</span>
          </div>
          <div class="col-md-6 text-center mb-3">
            <span class="fw-semibold text-center text-secondary details-nurdine">Telefone</span> <br />
            <span class="text-center">(+258) 84  563 6664</span>
          </div>
          <div class="col-md-6 text-center">
            <span class="fw-semibold text-center text-secondary details-nurdine">País</span> <br />
            <span class="text-center">Moçambique</span>
          </div>
          <div class="col-md-6 text-center">
            <span class="fw-semibold text-center text-secondary details-nurdine">Email</span> <br />
            <span class="text-center">nurdinebacar@gmail.com</span>
          </div>

          <div class="col-md-12 d-flex justify-content-center mt-5">
            <ul class="d-flex justify-content-between social-media">
              <li><a href="https://api.whatsapp.com/send?phone=258845636664" target="_blank"><i class="fa-brands fa-whatsapp"></i></a></li>
              <li><a href="https://www.linkedin.com/in/nurdine-bacar-58426425b/" target="_blank"><i class="fa-brands fa-linkedin"></i></a></li>
              <li><a href="mailto:nurdinebacar@gmail.com"><i class="fa-solid fa-envelope"></i></a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "about",
};
</script>

<style scoped>
img {
  height: 440px;
  min-height: auto;
}

ul li {
  list-style: none;
  margin: 0 10px;
}

ul li a {
  text-decoration: none;
  font-size: 25px;
  color: white;
}

ul li a:hover {
  color: gray;
}

.details-nurdine {
  border-left: 6px solid white;
  padding-left: 8px;
}

img{
  width: 60%;
  height: 70%;
  margin-left: 50px;
}

@media(max-width:420px) {
  img {
    margin-left: 48px;
  }

  p {
    text-align: center;
  }
  .social-media {
    margin-left: -37px;
  }
}
</style>
