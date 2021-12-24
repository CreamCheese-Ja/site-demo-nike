<template>
  <img :src="imageSrc" :alt="imageAlt" class="c-top-image" />
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
