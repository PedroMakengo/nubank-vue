<template>
  <div class="component">
    <Container>
      <Header />
      <Background class="background" />
    </Container>
    <ContainerMax>
      <CreditPersonal />
    </ContainerMax>
    <Container>
      <NubankCont />
    </Container>
    <Footer />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { Container, ContainerMax } from "@/components/bosons";
import {
  Header,
  Background,
  CreditPersonal,
  NubankCont,
  Footer,
} from "@/components/organisms";

export default defineComponent({
  components: {
    Container,
    ContainerMax,
    Header,
    Background,
    CreditPersonal,
    NubankCont,
    Footer,
  },
});
</script>

<style lang="scss" scoped>
/* Analisar com mais calma essa parte... */
.background {
  margin-top: 1rem;
}
</style>
