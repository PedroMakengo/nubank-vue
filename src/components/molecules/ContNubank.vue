<template>
  <div class="cont-nubank">
    <div class="nubank-image">
      <img
        src="@/assets/images/mobile-nubank.png"
        alt="Mão de um usuário pegando telefone"
      />
    </div>
    <div class="cont-describe">
      <h2>Conta do Nubank</h2>
      <p>A conta que vai levar você ao controle da sua vida financeira.</p>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({});
</script>

<style lang="scss" scoped>
.cont-nubank {
  background-color: #fff;
  background: url("@/assets/images/shadow-2.png");
  background-repeat: no-repeat;
  background-size: 100%;
  background-position-y: -0.6rem;

  display: grid;
  grid-template-columns: auto 1fr;

  .nubank-image {
    position: relative;
    transform: translateY(-20%);
    right: 40%;

    img {
      width: 100%;
    }
  }

  .cont-describe {
    padding-top: 4rem;
    font-family: Sora;
    transform: translateX(-40%);
    height: 10vh;

    padding: 7rem 0 0 0;

    h2 {
      font-size: 2rem;
      color: var(--bg-300);
    }

    p {
      width: 60%;
      font-size: 1rem;
      font-weight: 100;
    }
  }
}
</style>
