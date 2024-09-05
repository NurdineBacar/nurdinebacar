<template>
  <div class="">
    <navbar/>
    <banner/>
    <about/>
    <service/>
    <skills/>
    <contact/>
  </div>
</template>

<script>
import navbar from "./components/navbar.vue";
import banner from "./components/banner.vue";
import about from "./components/about.vue";
import service from "./components/service.vue";
import skills from "./components/skills.vue";
import contact from "./components/contact.vue";
import 'animate.css';

export default {
  name:"App",
  components:{
    navbar, banner,
    about, service,
    skills, contact,

  }
}
</script>

<style>
*{
  /* box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: Century Gothic; */
}
</style>