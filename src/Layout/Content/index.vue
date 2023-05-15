<template>
    <div class="xm-content">
      <div class="xm-content__items" v-for="item in 100">
          {{item}}
      </div>
    </div>
  </template>
  
  <script setup lang="ts">
  import { toRef, ref, reactive, computed } from "vue";
  </script>
  <style lang="scss">
      @include b(content){
          flex:1;
          overflow: auto;
          @include e(items){
              padding:10px;
              margin:10px;
              border:1px solid #ccc;
          }
      }
  </style>
  