<script setup lang="ts">
  import LogoComponent from './LogoComponent.vue';
  import ItemComponent from './ItemComponent.vue';
  import ProfileComponent from './ProfileComponent.vue';
</script>

<template>
  <header>
    <LogoComponent imageUrl="logo-lingui-academy.png"/>

    <nav>
      <ItemComponent></ItemComponent>
    </nav>

    <div>
      <ProfileComponent></ProfileComponent>
    </div>

  </header>
</template>
