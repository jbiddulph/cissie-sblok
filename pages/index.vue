<template>
  <div>
    <main role="main">
      <StoryblokComponent :blok="story.content" />
    </main>
    <h1>Hello</h1>
  </div>
</template>

<script setup lang="ts">
const story = await useStoryblok('home', {version : 'draft'})
</script>

<style scoped>

</style>