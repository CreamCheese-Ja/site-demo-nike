<template>
  <nuxt-link to="/" class="basic-button">{{ label }}</nuxt-link>
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
