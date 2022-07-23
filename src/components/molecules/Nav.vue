<template>
  <nav class="nav">
    <NavLink to="/home" text="Início" />
    <NavLink to="/home" text="Produtos" />
    <NavLink to="/home" text="Seu Negócio" />
    <NavLink to="/home" text="Nubank" />
    <NavLink to="/home" text="Perguntas" />
  </nav>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { NavLink } from "@/components/atoms";

export default defineComponent({
  components: { NavLink },
});
</script>

<style lang="scss" scoped>
.nav {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  grid-gap: 1rem;
}
</style>
