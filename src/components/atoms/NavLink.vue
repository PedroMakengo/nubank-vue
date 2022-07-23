<template>
  <a class="nav-link" :href="to">{{ text }}</a>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  props: {
    text: { Type: String, required: true },
    to: { Type: String, required: true },
  },
});
</script>
