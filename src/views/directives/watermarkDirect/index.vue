<template>
  <div v-waterMarker="{ text: 'Geeker Admin', textColor: 'rgba(180, 180, 180, 0.6)' }" class="card content-box">
    <span class="text">水印指令 🍇🍇🍇🍓🍓🍓</span>
  </div>
</template>

<script setup lang="ts">
defineOptions({ name: 'WatermarkDirect' })
</script>

<style scoped lang="scss">
@use './index';
</style>
