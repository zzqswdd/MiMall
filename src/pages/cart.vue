<template>
  <div>
    <order-header></order-header>
    cart
    <order-footer></order-footer>
  </div>
</template>

<script>
import OrderFooter from "@/components/order/OrderFooter.vue";
import OrderHeader from "@/components/order/OrderHeader.vue";
export default {
  name: "Cart",
  components: {
    OrderHeader,
    OrderFooter,
  },
};
</script>

<style scoped>
</style>