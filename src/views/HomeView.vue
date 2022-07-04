<template>
  <div class="home">
    <HelloWorld msg="Water plan" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/CoursesWorld.vue";
/* eslint-disable */ 
export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>
