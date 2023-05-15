<template>
  <div class="xm-box">
    <div>
      <Menu />
    </div>
    <div class="xm-box__right">
      <Header title="我是标题"/>
      <Content />
    </div>
  </div>
</template>

<script setup lang="ts">
import { ref, reactive } from "vue";
import Menu from "./Menu/index.vue";
import Header from "./Header/index.vue";
import Content from "./Content/index.vue";
</script>
<style scoped lang='scss'>
  @include b(box){
    @include bfc;
    display:flex;
    @include e(right){
      flex:1;
      display: flex;
      flex-direction:column;
     
    }
  }
</style>
