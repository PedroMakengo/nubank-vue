<template>
  <div class="footer-item">
    <h3>{{ title }}</h3>
    <a v-for="array of arrayList" :href="array.to" :key="array.id">
      {array.text}
    </a>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  props: {
    title: { Type: String, required: true },
    arrayList: { Type: [Object], required: true },
  },
});
</script>

<style lang="scss" scoped>
.footer-item {
}
</style>
