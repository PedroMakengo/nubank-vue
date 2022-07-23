<template>
  <div class="cart-credit">
    <img src="@/assets/images/nu-logo.svg" alt="" />
    <h1>
      Peça sua conta e cartão de credito do
      <span>Nubank</span>
    </h1>
    <p>
      Escolha o futuro. Comece a controlar melhor sua vida financeira com o
      Nubank.
    </p>

    <form>
      <label for="cpf">Digite seu <span>CPF</span></label>
      <div class="form-control">
        <input type="text" placeholder="228.885.288-78" />
        <button>Enviar</button>
      </div>
    </form>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({});
</script>

<style lang="scss" scoped>
.cart-credit {
  h1 {
    font-family: Sora;
    font-weight: 700;
    font-size: 2.6rem;
    margin: 0;

    color: #393939;

    span {
      color: var(--bg-100);
    }
  }

  p {
    width: 75%;
    font-size: 0.8rem;

    margin-block: 1.5rem;
  }

  form {
    label {
      margin-bottom: 1.5rem;
      display: flex;
    }

    .form-control {
      display: grid;
      grid-template-columns: 10rem 6rem;

      input {
        border-right: none;
        border: 1px solid var(--bg-900);
        border-radius: 0.5rem 0 0 0.5rem;
        padding: 0.4rem 0.6rem;
      }

      button {
        border-left: 0;
        border: 1px solid var(--bg-200);
        background: var(--bg-200);
        border-radius: 0 0.5rem 0.5rem 0;

        color: white;
      }
    }
  }
}
</style>
