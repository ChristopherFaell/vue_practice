<template>
  <div class="profile-container">
    <div class="profile-image">
      <img :src="profileImage" alt="Profile Image" />
    </div>
    <div class="dropdown">
      <button class="dropdown-button" @click="toggleDropdown">
        Menu
      </button>
      <ul v-if="isDropdownOpen" class="dropdown-list">
        <li class="dropdown-item">MY PROFILE</li>
        <li class="dropdown-item">SETTINGS</li>
        <li class="dropdown-item">LOG OUT</li>
      </ul>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent, ref } from 'vue';

export default defineComponent({
  name: 'ProfileComponent',
  setup() {
    const isDropdownOpen = ref(false);
    const profileImage = ref('https://via.placeholder.com/100'); // URL de la imagen de perfil

    const toggleDropdown = () => {
      isDropdownOpen.value = !isDropdownOpen.value;
    };

    return {
      isDropdownOpen,
      profileImage,
      toggleDropdown,
    };
  },
});
</script>

<style scoped>
.profile-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 150px;
}

.profile-image {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  overflow: hidden;
  margin-bottom: 10px;
}

.profile-image img {
  width: 100%;
  height: auto;
}

.dropdown {
  position: relative;
}

.dropdown-button {
  background-color: #007bff;
  color: white;
  border: none;
  padding: 10px;
  cursor: pointer;
  border-radius: 5px;
}

.dropdown-list {
  list-style-type: none;
  padding: 0;
  margin: 0;
  position: absolute;
  background-color: white;
  border: 1px solid #ccc;
  border-radius: 5px;
  width: 100%;
  z-index: 1;
}

.dropdown-item {
  padding: 10px;
  cursor: pointer;
}

.dropdown-item:hover {
  background-color: #f0f0f0;
}
</style>
