<template>
  <a class="social-link" :href="to">
    <img :src="getIcon" :alt="text" />
  </a>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  props: {
    icon: { Type: String, required: true },
    to: { Type: String, required: true },
    text: { Type: String, required: true },
  },

  methods: {
    getIcon() {
      return require(`@/assets/images/${this.icon}`);
    },
  },
});
</script>
