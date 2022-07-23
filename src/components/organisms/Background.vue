<template>
  <div class="background">
    <div class="content">
      <CartCredit class="cart-credit" />
      <img src="@/assets/images/card-user.png" class="user-card" alt="" />
    </div>
    <img src="@/assets/images/shadow.svg" alt="" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { CartCredit } from "@/components/molecules";

export default defineComponent({
  components: { CartCredit },
});
</script>

<style lang="scss" scoped>
.background {
  height: 77vh;
  background: white;
  background-image: url("@/assets/images/cards.svg");
  background-size: 40%;
  background-repeat: no-repeat;
  background-position-x: 26rem;
  background-position-y: 6rem;

  border-radius: 0.5rem 0.5rem 0 0;

  .content {
    display: grid;
    padding: 3rem;
    grid-template-columns: 1fr 1fr;
  }

  .user-card {
    width: 130%;
    position: relative;
    top: 10rem;
    left: 8rem;
    border: 0;
  }
}
</style>
