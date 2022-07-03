<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup


import MouseEffects from './components/MouseEffects.vue';

import Eletnav from './components/eletnav.vue';

</script>

<template>
  <Eletnav></Eletnav>
  


  
  <router-view></router-view>
  

  <MouseEffects></MouseEffects>

  <rout-link></rout-link>
</template>

<style>

</style>
