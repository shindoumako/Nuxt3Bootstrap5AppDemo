<template>
<div>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</div>
</template>

<style>
.page-enter-active,
.page-enter-active{
transition: all 0.4s;
}
.page-enter-from,
.page-leave-to{
opacity:0;
filter:blur(1rem);
}
</style>