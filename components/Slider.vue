<template>
  <div class="c-slider" :class="sliderSizeClass">
    <div class="operationArea">
      <h2 class="title">{{ sliderTitle }}</h2>
      <div class="buttonArea">
        <div class="button">
          <img
            src="../assets/images/allowButtonLeft.svg"
            alt=""
            class="buttonImage"
          />
        </div>
        <div class="button">
          <img
            src="../assets/images/allowButtonRight.svg"
            alt=""
            class="buttonImage"
          />
        </div>
      </div>
    </div>
    <div class="styleArea">
      <div v-for="item in sliderImages" :key="item" class="item">
        <img
          :src="require(`../assets/images/${item}`)"
          alt=""
          class="itemImage"
        />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  props: {
    sliderTitle: {
      type: String,
      default: "",
      required: true,
    },
    sliderImages: {
      type: Array,
      default: [],
      required: true,
    },
    sliderSizeClass: {
      type: String,
      default: "",
      required: true,
    },
  },
};
</script>
