<template>
  <nuxt-link to="/" class="basic-link">{{ label }}</nuxt-link>
</template>

<script lang="ts">
export default {
  props: {
    label: {
      type: String,
      default: "",
      required: true,
    },
  },
};
</script>
