<template>
  <div class="containerpage">
    列表
  </div>
</template>

<script>
import { reactive, toRefs } from "vue";
export default {
  components: {},
  setup() {
    const state = reactive({
  
    });
    return { ...toRefs(state) };
  },
};
</script>
<style lang="scss" scoped></style>
