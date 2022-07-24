<template>
  <div class="credit-personal">
    <DescribeCard class="describe-card" />
    <img
      src="@/assets/images/user-display-card.svg"
      class="card-user-display"
      alt="Moça mostrando o cartão dela do Nubank"
    />
    <img
      src="@/assets/images/card.svg"
      class="card"
      alt="Cartão do bano Nubank com apresentação do saldo"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

import { DescribeCard } from "@/components/molecules";

export default defineComponent({
  components: { DescribeCard },
});
</script>

<style lang="scss" scoped>
.credit-personal {
  background: linear-gradient(
    180deg,
    #9b30c2 0.01%,
    #9b30c2 0.02%,
    #820ad1 46.67%,
    #820ad1 72.76%,
    #7f26ba 100%
  );
  border-radius: 0.5rem;

  padding: 4rem;

  display: grid;
  grid-template-columns: auto auto auto;
  align-items: center;

  .describe-card {
    width: 270px;
  }

  .card-user-display {
    width: 318px;
    position: relative;
    transform: translateY(22.6%);
  }

  .card {
    width: 307px;
    transform: translateX(-10%);
  }
}
</style>
