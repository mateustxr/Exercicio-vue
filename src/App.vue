<script>
import MenuLateral from "@/components/MenuLateral.vue";
import MenuPrincipal from "./components/MenuPrincipal.vue";
import MenuFooter from "./components/MenuFooter.vue";
import MenuHeader from "./components/MenuHeader.vue";
export default {
  components: { MenuLateral, MenuPrincipal, MenuFooter, MenuHeader },
};
</script>
<template>
  <MenuLateral />
  <MenuPrincipal />
  <MenuFooter />
  <MenuHeader />
</template>
<style></style>
