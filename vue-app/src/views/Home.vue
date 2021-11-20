<template>
  <div class="home">
    <img alt="logo" src="../assets/logo.jpg" />
    <HelloWorld msg="Welcome to PostIt" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>

