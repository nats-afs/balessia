<template>
  <nav class="flex items-center justify-between flex-wrap bg-white-200 px-10 py-4 shadow-xl">
    <div class="flex items-center flex-shrink-0 text-black ml-10 mr-6">
      <img class="h-24" src="../assets/logo-facebook.png" alt="Monerias Balessia" />
      <!-- <span class="font-semibold text-xl tracking-tight">Monerias Balessia</span> -->
    </div>
    <div class="block lg:hidden">
      <button
        class="flex items-center px-3 py-2 border rounded text-teal-200 border-green-400 hover:text-white hover:border-white"
      >
        <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
          <title>Menu</title>
          <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
        </svg>
      </button>
    </div>
    <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
      <div class="text-center text-lg lg:flex-grow">
        <a
          href="#responsive-header"
          class="block mt-4 lg:inline-block lg:mt-0 text-orange-400 hover:text-orange-500 px-4"
        >Inicio</a>
        <a
          href="#responsive-header"
          class="block mt-4 lg:inline-block lg:mt-0 text-orange-400 hover:text-orange-500 px-4"
        >Nosotros</a>
        <a
          href="#responsive-header"
          class="block mt-4 lg:inline-block lg:mt-0 text-orange-400 hover:text-orange-500 px-4"
        >Galeria</a>
        <a
          href="#responsive-header"
          class="block mt-4 lg:inline-block lg:mt-0 text-orange-400 hover:text-orange-500 px-4"
        >Contacto</a>
      </div>
      <!-- <div>
        <a href="#" class="inline-block text-sm px-4 py-2 leading-none border rounded text-white border-white hover:border-transparent hover:text-teal-500 hover:bg-white mt-4 lg:mt-0">Download</a>
      </div>-->
    </div>
  </nav>
</template>
<script>
export default {};
</script>