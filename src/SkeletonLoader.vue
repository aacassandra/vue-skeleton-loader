<template>
  <div>
    <skeleton-box :width="width" :height="height" :circle="circle" />
  </div>
</template>
<script>
import SkeletonBox from './SkeletonBox.vue';

export default {
  components: {
    SkeletonBox
  },
  props: {
    width: {
      default: `100%`,
      type: String
    },
    height: {
      default: `100%`,
      type: String
    },
    circle: {
      default: false,
      type: Boolean
    }
  }
};
</script>
