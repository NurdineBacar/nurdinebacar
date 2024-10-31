<template>
    <div class="container-fluid bg-dark pt-4 pb-3 px-5" id="box">
      <div class="row text-white px-4">
        <h2 class="display-6 fw-semibold text-center mb-4" id="skills">Habilidades</h2>
  
          <div class="col-md-6 mb-5">
              <label for="" class="mb-1 fw-semibold"><img src="../assets/img/html.png" width="35" alt=""> HTML</label>
              <div class="w-100 bg-secondary box-item">
                  <div class="progress-bar item-sk" style="width:50%">50%</div>
              </div>
          </div>
          <div class="col-md-6 mb-5">
              <label for="" class="mb-1 fw-semibold"><img src="../assets/img/css.png" width="25" alt=""> CSS</label>
              <div class="w-100 bg-secondary box-item">
                  <div class="progress-bar item-sk" style="width:65%">65%</div>
              </div>
          </div>
          <div class="col-md-6 mb-5">
              <label for="" class="mb-1 fw-semibold"><img src="../assets/img/java.png" width="35" alt=""> Java</label>
              <div class="w-100 bg-secondary box-item">
                  <div class="progress-bar item-sk" style="width:45%">45%</div>
              </div>
          </div>
          <div class="col-md-6 mb-5">
              <label for="" class="mb-1 fw-semibold"><img src="../assets/img/javascript.png" width="35" alt=""> Javascript</label>
              <div class="w-100 bg-secondary box-item">
                  <div class="progress-bar item-sk" style="width:40%">40%</div>
              </div>
          </div>
          <div class="col-md-6 mb-5">
              <label for="" class="mb-1 fw-semibold"><img src="../assets/img/jquery.png" width="35" alt=""> JQuery</label>
              <div class="w-100 bg-secondary box-item">
                  <div class="progress-bar item-sk" style="width:65%">65%</div>
              </div>
          </div>
          <div class="col-md-6 mb-5">
              <label for="" class="mb-1 fw-semibold"><img src="../assets/img/vue.png" width="35" alt=""> Vue</label>
              <div class="w-100 bg-secondary box-item">
                  <div class="progress-bar item-sk" style="width:75%">75%</div>
              </div>
          </div>
          <div class="col-md-6 mb-4 fw-semibold">
              <label for="" class="mb-1"><img src="/img/wordpress.png" width="35" alt=""> Wordpress</label>
              <div class="w-100 bg-secondary box-item">
                  <div class="progress-bar item-sk" style="width:68%">68%</div>
              </div>
          </div>
          <div class="col-md-6 mb-4 fw-semibold">
              <label for="" class="mb-1"><img src="/img/php.png" width="35" alt=""> PHP</label>
              <div class="w-100 bg-secondary box-item">
                  <div class="progress-bar item-sk" style="width:60%">60%</div>
              </div>
          </div>
  
          <div class="col-md-12 px-5 text-center mt-4">
          
          </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "skills",
  };
  </script>
  
  <style scoped>
      .item-sk, .box-item{
          border-radius: 10px;
      }
      .item-sk{
          color: black;
          background: white;
      }
  
      .box-item:hover {
          border-color: gray;
          box-shadow: 0 0 10px rgba(255, 255, 255, 0.5);
      }

      #box{
        background: black;
      }
  </style>
  