<template>
  <nav
    class="top-0 fixed z-50 w-full flex flex-wrap items-center justify-between navbar-expand-lg"
  >
    <div
      class="w-full mx-auto flex flex-wrap items-center justify-between bg-red-600"
    >
      <div
        class="bg-white w-full relative flex justify-between lg:w-auto lg:static lg:block lg:justify-start"
      >
        <img
          src="../assets/img/g3pro.png"
          width="300px"
          alt="G3Ingenieria"
        />
        <button
          class="cursor-pointer text-xl leading-none px-5 py-1 border border-solid border-transparent rounded bg-transparent block lg:hidden outline-none focus:outline-none"
          type="button"
          v-on:click="toggleNavbar()"
        >
          <i class="text-gray-500 fas fa-bars"></i>
        </button>
      </div>
      <div
        class="lg:flex flex-grow items-center bg-white lg:bg-transparent lg:shadow-none"
        v-bind:class="{ hidden: !showMenu, block: showMenu }"
      >
        <ul class="flex flex-col lg:flex-row list-none lg:ml-auto">
          <li class="flex items-center">
            <a
              class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs"
              href="#pablo"
            >
              <i
                class="lg:text-gray-300 text-gray-500 fas fa-users text-xl leading-lg"
              ></i>
              <span class="inline-block text-xl ml-3">Nosotros</span></a
            >
          </li>
          <li class="flex items-center">
            <a
              class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs"
              href="#pablo"
              ><i
                class="lg:text-gray-300 text-gray-500 fab fa-twitter text-xl leading-lg"
              ></i
              ><span class="inline-block text-xl ml-3">Servicios</span></a
            >
          </li>
          <li class="flex items-center">
            <a
              class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs"
              href="#pablo"
              ><i
                class="lg:text-gray-300 text-gray-500 fab fa-github text-2xl leading-lg"
              ></i
              ><span class="inline-block text-xl ml-3">Clientes</span></a
            >
          </li>
          <li class="flex items-center">
            <a
              class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs"
              href="#pablo"
              ><i
                class="lg:text-gray-300 text-gray-500 fab fa-github text-2xl leading-lg"
              ></i
              ><span class="inline-block text-xl ml-3">Carreras</span></a
            >
          </li>
          <li class="flex items-center">
            <a
              class="mr-5 lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs"
              href="#pablo"
              ><i
                class="lg:text-gray-300 text-gray-500 fab fa-github text-2xl leading-lg"
              ></i
              ><span class="inline-block text-xl ml-3">Contactos</span></a
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
<script>
export default {
  data() {
    return {
      showMenu: false,
    };
  },
  methods: {
    toggleNavbar: function() {
      this.showMenu = !this.showMenu;
    },
  },
};
</script>
