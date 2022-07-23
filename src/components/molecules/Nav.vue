<template>
  <nav class="nav">
    <NavLink to="/home" text="Início" />
    <NavLink to="/home" text="Produtos" />
    <NavLink to="/home" text="Seu Negócio" />
    <NavLink to="/home" text="Nubank" class="active" />
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
  grid-template-columns: repeat(5, auto);
  justify-content: center;
  align-items: end;

  grid-gap: 2rem;

  a {
    color: white;
    opacity: 0.6;

    font-family: Poppins;
    transition: opacity 0.3s;

    &.active {
      opacity: 1;
      text-shadow: 0.3px 2px #0000005a;
    }

    &:hover {
      opacity: 1;
    }
  }
}
</style>
