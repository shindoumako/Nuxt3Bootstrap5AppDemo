<script lang="ts" setup>
useHead({
  title: 'Newt・Nuxtフォーム',
  meta: [
    { name: 'description', content: 'NewtとNuxtを利用した問い合わせフォームです' }
  ]
})
</script>

<template>
  <div class='container'>
    <h2>form</h2>
    <form action="https://Naturaldisasters.form.newt.so/v1/NMBwNi3OC" method="post">
      <p><label for="name">匿名</label></p>
      <input id="name" name="name">
     <p><label for="email">Email</label></p>
      <input id="email" name="email" type="email">
      <p><label for="message">コメント</label></p>
      <textarea id="message" name="message" />
      <p><button type="submit">
        送信
      </button></p>
    </form>
  </div>
</template>

<style scoped>
.container {
  font-family: arial;
  font-size: 20px;
  margin: 150px;
  width: 350px;
  height: 400px;
  outline: dashed 1px black;
}
</style>