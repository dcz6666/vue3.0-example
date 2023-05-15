<template>
    <div class="xm-menu">
     Menu
    </div>
  </template>
  
  <script setup lang="ts">
  import { toRef, ref, reactive, computed } from "vue";
  </script>
  <style lang="scss">
    @include b(menu){
      min-width:200px;
      border-right:1px solid #ccc;
      height:100%;
    }
  </style>
  