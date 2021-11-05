<template>
  <div>
    Home
    <nav-header></nav-header>
    <router-view></router-view>
    <nav-footer></nav-footer>
  </div>
</template>

<script>
import NavHeader from "@/components/nav/NavHeader.vue";
import NavFooter from "@/components/nav/NavFooter.vue";
export default {
  name: "Home",
  components: {
    NavHeader,
    NavFooter,
  },
};
</script>

<style scoped>
</style>