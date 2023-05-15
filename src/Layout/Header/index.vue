<template>
    <div class="xm-header">
     header
    </div>
  </template>
  
  <script setup lang="ts">
  import { toRef, ref, reactive, computed } from "vue";
  </script>
  <style lang="scss">
      @include b(header){
          height: 60px;
          border-bottom:1px solid #ccc;
      }
  </style>
  