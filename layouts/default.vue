<template>

  <div>
    <AppHeader />
    <AppAside />
    <slot />
    <AppFooter />
  </div>
</template>

<template>
  <header>header</header>
  <main>
   <slot />
  </main>
  <footer>Footer</footer>
</template>