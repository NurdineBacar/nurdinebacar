<template>
  <div class="container-fluid pt-4 pb-5 px-5 service">
    <div class="row text-white">
      <h2 class="display-6 fw-semibold text-center">Serviços</h2>
      <span class="text-center text-secondary mb-5">- Meus serviços para clientes -</span>
      <div class="col-md item-service bg-dark py-3 me-3 mb-3">
        <div class="row">
          <div>
            <img src="../assets/img/pc.png" width="70px" class="img-service my-3" alt=""/>
          </div>
          <h3 class="text-center text-white fw-semibold display-6 fs-6 mb-3">
            DESENVOLVEDOR DE APLICATIVOS DESKTOP
          </h3>
          <p class="fs-6 text-center px-5">
            Com habilidades sólidas em várias tecnologias de DESKTOP, estou pronto para criar soluções personalizadas que atendam às suas necessidades específicas. Vamos transformar sua visão em realidade!
          </p>
        </div>
      </div>
      <div class="col-md item-service bg-dark py-3 me-3 mb-3">
        <div class="row">
          <div>
            <img src="../assets/img/dominio.png" width="70px" class="img-service my-3" alt=""/>
          </div>
          <h3 class="text-center text-white fw-semibold display-6 fs-6 mb-3">
            DESENVOLVEDOR WEB
          </h3>
          <p class="fs-6 text-center px-5">
            Com experiência em várias linguagens e tecnologias web, estou pronto para desenvolver sistemas web dinâmicos, responsivos e visualmente cativantes. Vamos colaborar para tornar sua presença online impactante!
          </p>
        </div>
      </div>
      <div class="col-md item-service bg-dark py-3 mb-3">
        <div class="row">
          <div>
            <img src="../assets/img/web-design.png" width="70px" class="img-service my-3" alt=""/>
          </div>
          <h3 class="text-center text-white fw-semibold display-6 fs-6 mb-3">
            DESIGN WEB
          </h3>
          <p class="fs-6 text-center px-5">
            Com experiência em várias linguagens e tecnologias web, estou pronto para desenvolver sites dinâmicos, responsivos e visualmente cativantes.
          </p>
        </div>
      </div>

      <div class="col-md-12 text-center mt-4">
        <p class="w-75 mx-auto sv-text">
          Ofereço uma gama de serviços especializados em desenvolvimento web, desde a criação de sites personalizados até a otimização da experiência do usuário. Minhas habilidades incluem design responsivo, desenvolvimento frontend e backend.
          Estou comprometido em fornecer soluções de alta qualidade que atendam às necessidades únicas de meus clientes e ajudem a alcançar seus objetivos online.
        </p>
        <button class="button fw-semibold">
          <a href="https://api.whatsapp.com/send?phone=258845636664" target="_blank">Entrar em Contato <i class="ms-1 fa-solid fa-phone"></i></a>
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "service",
};
</script>

<style scoped>
.service {
  background: black;
}

.item-service {
  border-bottom: 4px solid white;
}

.item-service:hover {
  border-color: gray;
  box-shadow: 0 0 10px rgba(255, 255, 255, 0.5);
}

.img-service {
  margin-left: 150px;
}

.button {
  padding: 9px 20px;
  border: 2px solid white;
  background: transparent;
  position: relative;
}

.button:hover {
  background-color: white;
  transition: .75s ease-in;

  &>*:hover {
    color: black;
  }
}

.button a {
  text-decoration: none;
  color: white;
}

@media (max-width: 420px) {
  .sv-text {
    width: 80%;
  }
  .img-service {
    margin-left: 110px;
  }
}
</style>
