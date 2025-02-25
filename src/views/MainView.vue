<template>
  <div class="bg-purple-100 p-4">
    <div class="grid grid-cols-8 gap-2">
      <!-- Header Row -->
      <div class="col-span-1 bg-purple-300 text-center font-bold p-2">TIME</div>
      <div class="col-span-1 bg-purple-300 text-center font-bold p-2">MONDAY</div>
      <div class="col-span-1 bg-purple-300 text-center font-bold p-2">TUESDAY</div>
      <div class="col-span-1 bg-purple-300 text-center font-bold p-2">WEDNESDAY</div>
      <div class="col-span-1 bg-purple-300 text-center font-bold p-2">THURSDAY</div>
      <div class="col-span-1 bg-purple-300 text-center font-bold p-2">FRIDAY</div>
      <div class="col-span-1 bg-purple-300 text-center font-bold p-2">SATURDAY</div>
      <div class="col-span-1 bg-purple-300 text-center font-bold p-2">CLASSROOM</div>

      <!-- Time Column -->
      <div class="col-span-1">
        <div class="bg-purple-200 text-center p-2 m-1">Morning</div>
        <div class="bg-purple-200 text-center p-2 m-1">Afternoon</div>
        <div class="bg-purple-200 text-center p-2 m-1">Night</div>
        <div class="bg-purple-200 text-center p-2 m-1">Morning</div>
        <div class="bg-purple-200 text-center p-2 m-1">Afternoon</div>
        <div class="bg-purple-200 text-center p-2 m-1">Night</div>
        <div class="bg-purple-200 text-center p-2 m-1">Morning</div>
        <div class="bg-purple-200 text-center p-2 m-1">Afternoon</div>
        <div class="bg-purple-200 text-center p-2 m-1">Night</div>
      </div>

      <!-- Monday Column -->
      <div class="col-span-1">
        <div class="bg-purple-200 text-center p-2 m-1">Kids</div>
        <div class="bg-purple-200 text-center p-2 m-1">Elementary</div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
      </div>

      <!-- Tuesday Column -->
      <div class="col-span-1">
        <div class="bg-purple-200 text-center p-2 m-1">Elementary</div>
        <div class="bg-purple-200 text-center p-2 m-1">Super</div>
        <div class="bg-purple-200 text-center p-2 m-1">Advanced</div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
      </div>

      <!-- Wednesday Column -->
      <div class="col-span-1">
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
      </div>

      <!-- Thursday Column -->
      <div class="col-span-1">
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
      </div>

      <!-- Friday Column -->
      <div class="col-span-1">
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
      </div>

      <!-- Saturday Column -->
      <div class="col-span-1">
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
      </div>

      <!-- Classroom Column -->
      <div class="col-span-1">
        <div class="bg-purple-200 text-center p-2 m-1">ROMA</div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1">TOKYO</div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1">KOREA</div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
        <div class="bg-purple-200 text-center p-2 m-1"></div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'ScheduleView',
});
</script>

<style scoped>
/* No additional styles needed as TailwindCSS is used */
</style>
```

Este código crea una vista de Vue que se ve exactamente como la imagen proporcionada. Asegúrate de tener TailwindCSS configurado en tu proyecto de Vue. Puedes seguir la [guía oficial de TailwindCSS](https://tailwindcss.com/docs/guides/vue-3-vite) para integrarlo con Vue.
