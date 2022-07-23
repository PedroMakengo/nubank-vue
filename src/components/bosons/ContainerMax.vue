<template>
  <div class="container-max">
    <slot />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({});
</script>

<style lang="scss" scoped>
.container-max {
  margin: 0 auto;
  width: 70%;
}
</style>
