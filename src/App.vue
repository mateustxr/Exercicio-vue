<script>
import MenuLateral from "@/components/MenuLateral.vue";
import BlocoPrincipal from "./components/BlocoPrincipal.vue";
export default {
  components: { MenuLateral, BlocoPrincipal },
};
</script>
<template>
  <MenuLateral />
  <header id="header">Cabeçalho</header>
  <main id="content">Principal</main>
  <footer id="footer">Rodapé</footer>
  <BlocoPrincipal />
</template>
<style></style>
