<template>
  <div class="nubank-cont">
    <ContNubank />
    <img src="@/assets/images/mobile.svg" class="c" alt="" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { ContNubank } from "@/components/molecules";

export default defineComponent({
  components: { ContNubank },
});
</script>

<style lang="scss" scoped>
.nubank-cont {
  background: #fff;
  height: calc(max(min(100vh)) + 8rem);

  border-radius: 0 0 0.5rem 0.5rem;
  img {
    width: 100%;
    transform: translateY(-32%);
  }
}
</style>
