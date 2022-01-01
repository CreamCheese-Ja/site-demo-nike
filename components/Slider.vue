<template>
  <div class="slider">
    <div class="operation-area">
      <h2 class="title">{{ sliderTitle }}</h2>
      <div class="button-area">
        <div class="button">
          <img
            src="../assets/images/allowButtonLeft.svg"
            alt=""
            class="button-image"
          />
        </div>
        <div class="button">
          <img
            src="../assets/images/allowButtonRight.svg"
            alt=""
            class="button-image"
          />
        </div>
      </div>
    </div>
    <div class="item-area">
      <div v-for="item in sliderImages" :key="item" class="item">
        <img
          :src="require(`../assets/images/${item}`)"
          alt=""
          class="item-image"
        />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { PropType } from "vue";
export default {
  props: {
    sliderTitle: {
      type: String,
      default: "",
      required: true,
    },
    sliderImages: {
      type: Array as PropType<string[]>,
      default: () => [],
      required: true,
    },
  },
};
</script>
