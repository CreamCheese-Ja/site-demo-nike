<template>
  <nuxt-link to="/" class="footer-icon-area">
    <svg
      xmlns="http://www.w3.org/2000/svg"
      class="icon"
      fill="currentColor"
      viewBox="0 0 24 24"
    >
      <path :d="path"></path>
    </svg>
  </nuxt-link>
</template>

<script lang="ts">
export default {
  props: {
    path: {
      type: String,
      default: "",
      required: true,
    },
  },
};
</script>
