<template>
  <div class="background">
    <div class="content">
      <CardCredit />
      <img src="@/assets/images/card-user.png" class="user-card" alt="" />
    </div>
    <div class="shadow"></div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { CardCredit } from "@/components/molecules";

export default defineComponent({
  components: { CardCredit },
});
</script>

<style lang="scss" scoped>
.background {
  /* height: auto; */
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

  .shadow {
    background: url("@/assets/images/shadow.svg");
    background-size: 100%;
    background-repeat: no-repeat;
    background-position: center;
    background-position-x: -1rem;
    width: 100%;
    height: 8vh;

    display: grid;
  }
}
</style>
