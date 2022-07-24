<template>
  <footer class="footer">
    <Container>
      <h1>Footer</h1>
    </Container>
  </footer>
</template>

<script lang="ts">
import { defineComponent } from "vue";

import { Container } from "@/components/bosons";

export default defineComponent({
  components: { Container },
});
</script>

<style lang="scss" scoped>
.footer {
  background: #30004f;
  height: 50vh;
}
</style>
