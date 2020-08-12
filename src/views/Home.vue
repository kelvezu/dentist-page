<template>
  <div class="bg-gray-800">
    <img alt="Vue logo" src="../assets/dentist_logo.png" />
    <HelloWorld msg="Welcome to The Dentist Page" />
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
