<script setup>
</script>
<template>
  <div>
    <BCarousel controls indicators>
  <BCarouselSlide img-src="https://picsum.photos/1024/480/?image=7" caption="First Caption" />
  <BCarouselSlide img-src="https://picsum.photos/1024/480/?image=9">
    <template #caption> Second Caption </template>
  </BCarouselSlide>
</BCarousel>
  </div>
</template>
<style scoped>
</style>
