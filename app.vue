<template>
<div>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</div>
</template>

/pages
  ┝ /user
  │  ┝ [id].vue    →  /user/{id}
  │  ┝ edit.vue    →  /user/edit
  │  └ index.vue   →  /user
  ┝ about.vue       →  /about
  └ index.vue       →  /

  <script setup>
const route = useRoute()
const id = route.params.id
 </script>

 <NuxtLink to="/about">about</NuxtLink>

 const router= useRouter()
router.back()  //1つ戻る
router.forward()  //1つ進む
router.go(1)  //引数の数値分進む（戻る）
router.push('/about')  //指定したパスに遷移
router.replace('/about')  //指定したパスに置換

navigateTo('/about')

navigateTo({
  path:'/about',
  query:{
    param1:1,
    param2:'abc'
  }
})

<script setup>
useHead({
  title:'About Page',
  meta:[
    { name:'description', content:'Aboutのページです。'}
  ]
})
</script>

<template>
 <Head>
    <Title>{{ title }}</Title>
    <Meta name="description" :content="description"/>
  </Head>
  <div class="contents">
  </div>
</template>

<script setup>
const title= 'About Page'
const description= 'Aboutのページです。'
</script>
