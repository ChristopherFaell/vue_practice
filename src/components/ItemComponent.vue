<template>
  <nav class="navbar">
    <ul class="menu">
      <li class="menu-item">About Us</li>
      <li class="menu-item">Space</li>
      <li class="menu-item">Languages</li>
      <li class="menu-item">Network</li>
      <li class="menu-item">Lingui Site</li>
    </ul>
  </nav>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HorizontalMenu',
});
</script>

<style scoped>
.navbar {
  background-color: #333;
  padding: 10px;
}

.menu {
  list-style-type: none;
  display: flex;
  justify-content: space-around;
  margin: 0;
  padding: 0;
}

.menu-item {
  color: white;
  text-decoration: none;
  padding: 10px 20px;
  cursor: pointer;
}

.menu-item:hover {
  background-color: #575757;
}
</style>
