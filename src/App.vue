<template>
  <HeaderComponent></HeaderComponent>
  <main>
    <RouterView></RouterView>
  </main>
  <FooterComponent></FooterComponent>
</template>

<script setup>
import HeaderComponent from './components/HeaderComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
</script>

<style scoped lang="scss"></style>