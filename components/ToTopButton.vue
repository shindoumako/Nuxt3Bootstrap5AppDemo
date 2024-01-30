<template>
    <button @click="scrollToTop" v-show="showButton" class="to-top-button">
      To Top
    </button>
  </template>
  
  <script setup>
  import { ref, onMounted, onUnmounted } from 'vue';
  
  const showButton = ref(false);
  
  const onScroll = (e) => {
    const top = window.pageYOffset || e.target.scrollTop || 0;
    showButton.value = top > 500;
  };
  
  const scrollToTop = () => {
    window.scrollTo({
      top: 0,
      behavior: 'smooth',
    });
  };
  
  onMounted(() => {
    window.addEventListener('scroll', onScroll);
  });
  
  onUnmounted(() => {
    window.removeEventListener('scroll', onScroll);
  });
  </script>
  <style scoped>
  .to-top-button {
    background-color: rgba(0, 102, 255, 0.507);
    color: white;
    /* 他のスタイルも追加できます */
  }
  </style>