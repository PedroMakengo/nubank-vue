<template>
  <div class="component">
    <Container>
      <Header />
      <Background class="background" />
    </Container>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Container } from "@/components/bosons";
import { Header, Background } from "@/components/organisms";

export default defineComponent({
  components: { Container, Header, Background },
});
</script>

<style lang="scss" scoped>
/* Analisar com mais calma essa parte... */
.background {
  margin-top: 1rem;
}
</style>
