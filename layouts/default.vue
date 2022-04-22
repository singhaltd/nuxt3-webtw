<script setup>
    const route = useRoute();

    useHead({
    meta: [{ name: "og:title", content: `App Name - ${route.meta.title}` }],
    });
</script>

<template>
  <div>
    <NavbarMega />
    <NuxtPage />
    <FooterTwof />
  </div>
</template>