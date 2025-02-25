<script setup lang="ts">
import { RouterView } from 'vue-router'
import FooterComponent from '@/components/FooterComponent.vue';
import HeaderComponentTwo from '@/components/HeaderComponentTwo.vue';
import ItemComponent from '@/components/ItemComponent.vue';
</script>

<template>
  <div class="main-container">
    <HeaderComponentTwo />

    <aside>
      <ItemComponent></ItemComponent>
    </aside>

    <section class="main-content">
      <RouterView />
    </section>

    <FooterComponent />
  </div>
</template>
