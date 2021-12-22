<template>
  <a href="">
    <button class="c-header-icon-button">
      <img :src="imageSrc" :alt="imageAlt" class="icon" />
    </button>
  </a>
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
