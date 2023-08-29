<script setup lang="ts">
import { RouterView } from 'vue-router'
import NavBarVue from './components/NavBar.vue'
import FooterViewVue from './components/FooterView.vue'
</script>

<template>
  <NavBarVue />
  <RouterView />
  <FooterViewVue />
</template>

<style scoped></style>
