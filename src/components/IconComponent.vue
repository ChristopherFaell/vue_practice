<template>
  <div class="sidebar">
    <ul class="icon-list">
      <li class="icon-item">📅 CALENDARIO</li>
      <li class="icon-item">📈 AVANCE</li>
      <li class="icon-item">📊 REPORTES</li>
      <li class="icon-item">⚙️ SETTINGS</li>
      <li class="icon-item">🛠️ SOPORTE</li>
      <li class="icon-item">ℹ️ INFORMACION</li>
    </ul>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'VerticalIconMenu',
});
</script>

<style scoped>
.sidebar {
  width: 200px;
  background-color: #f4f4f4;
  padding: 10px;
  border-right: 1px solid #ccc;
}

.icon-list {
  list-style-type: none;
  padding: 0;
  margin: 0;
}

.icon-item {
  padding: 10px;
  cursor: pointer;
  display: flex;
  align-items: center;
}

.icon-item:hover {
  background-color: #ddd;
}
</style>
