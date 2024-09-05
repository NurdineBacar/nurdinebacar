<template>
  <div class="container-fluid pt-4 pb-5 px-5" id="service">
    <div class="row text-white">
      <h2 class="display-6 fw-semibold text-center">Services</h2>
      <span class="text-center text-secondary mb-5">- My services for clients -</span>
      <div class="col-md item-service bg-dark py-3 me-3 mb-3">
        <div class="row">
          <div>
            <img src="/img/pc.png" width="70px" class="img-service my-3" alt=""/>
          </div>
          <h3 class="text-center text-white fw-semibold display-6 fs-6 mb-3">
            DESKTOP APP DEVELOPER
          </h3>
          <p class="fs-6 text-center px-5">
            With solid skills in a some of technologies DESKTOP, I am ready to create custom desktop solutions that meet your specific needs. Let's turn your vision into reality!
          </p>
        </div>
      </div>
      <div class="col-md item-service bg-dark py-3 me-3 mb-3">
        <div class="row">
          <div>
            <img src="/img/dominio.png" width="70px" class="img-service my-3" alt=""/>
          </div>
          <h3 class="text-center text-white fw-semibold display-6 fs-6 mb-3">
            WEB DEVELOPER
          </h3>
          <p class="fs-6 text-center px-5">
            With experience in several languages ​​and web technologies, I am ready to develop dynamic, responsive and visually captivating web systems. Let's collaborate to make your online presence impactful!
          </p>
        </div>
      </div>
      <div class="col-md item-service bg-dark py-3 mb-3">
        <div class="row">
          <div>
            <img src="/img/web-design.png" width="70px" class="img-service my-3" alt=""/>
          </div>
          <h3 class="text-center text-white fw-semibold display-6 fs-6 mb-3">
            WEB DESIGN
          </h3>
          <p class="fs-6 text-center px-5">
            With experience in several languages ​​and web technologies, I am ready to develop dynamic, responsive and visually captivating websites.
          </p>
        </div>
      </div>

      <div class="col-md-12 text-center mt-4">
        <p class="w-75 mx-auto sv-text">I offer a range of specialist web development services, from creating custom websites to optimizing user experience. My skills include responsive design, frontend and backend development.
I am committed to providing high-quality solutions that meet my clients' unique needs and help them achieve their goals online.</p>
            <button class="button fw-semibold"><a href="https://api.whatsapp.com/send?phone=258845636664" target="_blank">Get in Contact <i class="ms-1 fa-solid fa-phone"></i></a></button>
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
#service {
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

.button{
    padding: 9px 20px;
    border: 2px solid white;
    background: transparent;
    position: relative;
}

.button:hover{
    background-color: white;
    transition: .75s ease-in;

    &>*:hover{
      color: black;
    }
}

.button a{
  text-decoration: none;
  color: white;
}



@media(max-width:420px){
    .sv-text{
        width: 80%;
    }
    .img-service{
      margin-left: 110px;
    }
}
</style>