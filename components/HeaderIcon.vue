<template>
  <nuxt-link to="">
    <button class="header-icon-button">
      <img :src="imageSrc" :alt="imageAlt" class="icon" />
    </button>
  </nuxt-link>
</template>

<script lang="ts">
export default {
  props: {
    imageSrc: {
      type: String,
      default: "",
      required: true,
    },
    imageAlt: {
      type: String,
      default: "",
      required: true,
    },
  },
};
</script>
