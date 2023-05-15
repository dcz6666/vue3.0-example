<template>
  <Layout></Layout>
</template>

<script setup lang="ts">
import { toRef, ref, reactive, computed } from "vue";
import Layout from "./Layout/index.vue";
let keyWord = ref("");
</script>
<style lang="scss">
#app {
  @include bfc;
}
</style>
