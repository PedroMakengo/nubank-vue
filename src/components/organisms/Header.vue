<template>
  <header class="header">
    <Nav />
  </header>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Nav } from "@/components/molecules";

export default defineComponent({
  components: { Nav },
});
</script>

<style lang="scss" scoped>
.header {
  background: red;
}
</style>
