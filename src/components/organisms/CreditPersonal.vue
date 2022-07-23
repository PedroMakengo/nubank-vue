<template>
  <div class="credit-personal">
    <DescribeCard />
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
  padding-block: 2rem;
  border-radius: 0.5rem;

  padding: 3rem;
}
</style>
