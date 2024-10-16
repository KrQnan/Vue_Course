<template>
  <NavbarComponent></NavbarComponent>
  <RouterView v-slot="{ Component }" class="m-8">
    <Transition>
      <component :is="Component" />
    </Transition>
  </RouterView>
  <FooterComponent></FooterComponent>
</template>

<script setup lang="ts">
import { RouterView } from 'vue-router'
import NavbarComponent from './components/general/NavbarComponent.vue'

</script>

<style scoped></style>
