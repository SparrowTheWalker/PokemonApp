<template>
  <div class="p-14">
    <router-link class="flex justify-center text-4xl text-yellow-700" to="/">Pokemon Picker</router-link>
    <HomeView/>
  </div>
  <router-view/>
</template>

<script>
import HomeView from "./views/Home.vue";

export default {
  name: "App",
  components: {
    HomeView,
  },
};
</script>

<style></style>
