<template>
  <TheNave />
  <router-view />
</template>

<script>
import TheNave from "@/components/TheNave.vue";
export default {
  components: {
    TheNave,
  },
};
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  box-sizing: border-box;
  font-family: "Montserrat", sans-serif;
  color: #0c0c0c;
  background-color: #ffffff;
  overflow-x: hidden;
}
#app h1,
#app h2 {
  font-family: "Playfair Display", serif;
}
#app a,
#app a:hover,
#app a:focus {
  text-decoration: none;
}


#app .btn,
#app .btn:focus {
  outline: none !important;
  -webkit-box-shadow: none;
  box-shadow: none;
}
@media (min-width: 1200px) {
  #app .container {
    max-width: 1170px !important;
  }
}
</style>
