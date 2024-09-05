<template>
  <div class="container-fluid bg-dark pt-4 pb-3 px-5">
    <div class="row g-1 text-white">
      <h2 class="display-6 fw-semibold text-center mb-3" id="about">About</h2>
      <div class="col-md-5">
        <img src="/img/men.png" class="rounded  w-75" alt=""
        />
      </div>
      <div class="col-md me-3">
        <div class="row fs-6">
          <div class="col-md-12 mb-3">
            <p>
              Hello! I'm Nurdine Aboo Bacar, a systems development enthusiast. With remarkable skill in some web and desktop languages, such as HTML, CSS and Java. I am constantly exploring new techniques and trends to improve my skills.

I am always ready to face challenges and dive into new projects, finding creative solutions to complex problems. I believe that learning is a continuous journey and I am always looking to expand my horizons and improve myself.

I have a laid-back personality and love sharing laughs with teammates as we work together on exciting projects. I am always open to new collaboration opportunities and look forward to being part of dynamic and innovative teams.
            </p>
          </div>
          <div class="col-md-6 text-center mb-3">
            <span class="fw-semibold text-center text-secondary details-nurdine">Name</span> <br />
            <span class="text-center">Nurdine Aboo Bacar</span>
          </div>
          <div class="col-md-6 text-center mb-3">
            <span class="fw-semibold text-center text-secondary details-nurdine">Phone</span> <br />
            <span class="text-center">(+258) 84  563 6664</span>
          </div>
          <div class="col-md-6 text-center">
            <span class="fw-semibold text-center text-secondary details-nurdine">Country</span> <br />
            <span class="text-center">Mozambique</span>
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

ul li{
    list-style: none;
    margin: 0 10px;
}

ul li a{
  text-decoration: none;
  font-size: 25px;
  color: white;

  &:hover{
    color: gray;
  }
}

.details-nurdine{
  border-left: 6px solid white;
  padding-left: 8px;
}

@media(max-width:420px){
  img{
    margin-left: 45px;
  }

  p{
    text-align: center;
  }
  .social-media{
    margin-left: -37px;
  }
}
</style>