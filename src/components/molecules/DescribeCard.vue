<template>
  <div class="describe-card">
    <h2>Cartão de Crédito Pode chamar ele de roxinho.</h2>
    <p>Além disso, pode chamar ele de moderno, gratuito e prático também.</p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({});
</script>

<style lang="scss" scoped>
.describe-card {
  color: #fff;
  h2 {
    font-size: 2.2rem;
    width: 90%;
    margin-bottom: 1rem;
  }

  p {
    width: 100%;
    padding-inline: 1rem;

    opacity: 0.6;
  }
}
</style>
