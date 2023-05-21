<template>
  <div>HOME</div>
</template>
<script>
import { computed, onMounted, ref, watch } from "vue";
export default {
  name: "Home",
  props: {},
  setup() {
    const movePosition = () => {};
    onMounted(() => {
      console.log(`mounted`);
    });
    return {
      movePosition,
    };
  },
};
</script>