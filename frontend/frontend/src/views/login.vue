<template>
  <div>
    <Heders />
  </div>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <Login />
    <!--msg="Welcome to Your Vue.js App"-->
  </div>
</template>

<script>
// @ is an alias to /src
import Login from "@/components/Login.vue";
import Heders from "@/components/heder.vue";

export default {
  name: "HomeView",
  components: {
    Login,
    Heders,
  },
};
</script>
