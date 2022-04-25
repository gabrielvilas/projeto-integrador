<script>
import MenuLateral from "@/components/MenuLateral.vue";
import CompPrincipal from "@/components/CompPrincipal.vue";
import CompCabeca from "./components/CompCabeca.vue";
import CompFuteer from "./components/CompFuteer.vue";
export default {
  components: { MenuLateral, CompPrincipal, CompCabeca, CompFuteer },
};
</script>
<template>
  <CompPrincipal />
  <MenuLateral />
  <CompCabeca />
  <CompFuteer />
</template>
<style></style>
