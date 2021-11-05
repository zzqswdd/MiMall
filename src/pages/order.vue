<template>
  <div>
    <order-header></order-header>
    <router-view></router-view>
    <nav-footer></nav-footer>
  </div>
</template>

<script>
import OrderHeader from "@/components/order/OrderHeader.vue";
import NavFooter from "@/components/nav/NavFooter.vue";

export default {
  name: "Order",
  components: {
    OrderHeader,
    NavFooter,
  },
};
</script>

<style scoped>
</style>