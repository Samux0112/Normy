<script setup>
import Footer from '~/components/global/Footer.vue';
useHead({
  htmlAttrs: {
    lang: 'en',
  },
  meta: [
    { property: 'og:title', content: `Normy DMorales` },
    { name: 'description', content: 'Soy Normy DMorales “Servir es mi pasión y dejar huella es mi misión”' },
  ],
  title: `Normy DMorales`,
})
</script>

<template>
  <main class="max-w-8xl">
    <slot/>
    <Footer />
  </main>
</template>
