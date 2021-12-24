<template>
  <a href="" class="c-basic-link">{{ label }}</a>
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
