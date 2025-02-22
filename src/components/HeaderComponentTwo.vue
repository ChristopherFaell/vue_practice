<script setup lang="ts">
  import IconComponent.vue from './IconComponent.vue';
  import LogoComponent from './LogoComponent.vue';
  import ProfileComponent from './ProfileComponent.vue';
</script>

<template>
<header>
  <LogoComponent imageUrl="logo-lingui-academy.png"/>
  <div class="flags">
    <FlagsComponent imageUrl="reino-unido.png" />
    <FlagsComponent imageUrl="francia.png" />
    <FlagsComponent imageUrl="italia.png" />
    <FlagsComponent imageUrl="alemania.png" />
    <FlagsComponent imageUrl="brasil.png" />
  </div>
</header>
</template>
