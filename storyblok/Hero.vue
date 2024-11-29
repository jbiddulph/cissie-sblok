<template>
  <div class="hero" v-editable="blok">
    <div class="grid grid-cols-2 mx-auto container">
      <img src="" alt="">
      <div>
        xxx
        <h1>{{ blok }}</h1>
        xxx
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
defineProps({
  blok: Object, 
  default: () => ({})
})
</script>