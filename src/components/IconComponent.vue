<script setup lang="ts">
  const props = defineProps<{
    imageUrl: string
  }>()
  const imageSrc = new URL(`../assets/${props.imageUrl}`, import.meta.url).href
</script>

<template>
  <img :src="imageSrc" alt="Icon Images" class="icon-image" />
</template>

<style scoped>
  .icon-image {
    width: 35px;
    height: 35px;
  }
</style>
