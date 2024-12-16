<template>
  <div class="w-full h-auto bg-[#131313]">
    <v-footer class="flex flex-column bg-transparent text-white">
      <div class="flex px-4">
        <a href="#inicio">
          <strong class="text-xl">Ramon Insua</strong>
        </a>
        <ul>
          <li>

          </li>
          <li>

          </li>
          <li>
            
          </li>
        </ul>
      </div>
  
      <div class="px-4 py-2 text-center w-100">
        {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
      </div>
    </v-footer>
  </div>
</template>

    <script>
  export default {
    data: () => ({
      icons: [
        'mdi-facebook',
        'mdi-twitter',
        'mdi-linkedin',
        'mdi-instagram',
      ],
    }),
  }
</script>