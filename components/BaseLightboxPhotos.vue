<template>
  <div class="light-box-photos-container">
    <lightbox
      class="mt-3"
      :cells="cells"
      :items="items"
    ></lightbox>
  </div>
</template>

<script>
import Vue from "vue";
export default {
  props: {
    cells: {
      type: Number,
      default: 1,
    },
    items: {
      type: Array,
    },
  },
};
</script>

<style lang="stylus" scoped>
.light-box-photos-container {
  & >>> div {
    height: 160px;
    margin: 0;
  }
}
</style>