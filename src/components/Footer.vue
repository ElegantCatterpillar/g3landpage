<template>
  <footer class="relative bg-red-600 pt-8 pb-6">
    <div
      class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20"
      style="height: 80px; transform: translateZ(0px);"
    >
      <svg
        class="absolute bottom-0 overflow-hidden"
        xmlns="http://www.w3.org/2000/svg"
        preserveAspectRatio="none"
        version="1.1"
        viewBox="0 0 2560 100"
        x="0"
        y="0"
      >
        <polygon
          class="text-red-600 fill-current"
          points="2560 0 2560 100 0 100"
        ></polygon>
      </svg>
    </div>
    <div class="container mx-auto px-4">
      <div class="flex flex-wrap">
        <div class="w-full lg:w-6/12 px-4">
          <h4 class="text-3xl font-semibold text-white">
            ¡Mantengámonos en contacto!
          </h4>
          <h5 class="text-lg mt-0 mb-2 text-white font-semibold">
            Encuéntrenos en cualquiera de nuestras Redes Sociales!
          </h5>
          <div class="mt-6">
            <button
              class="bg-blue-400 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1"
              type="button"
            >
              <i class="fab fa-twitter"></i></button
            >
            <button
              class="bg-blue-700 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1 ml-2"
              type="button"
            >
              <i class="fab fa-linkedin-in"></i></button
            >
            <button
              class="bg-blue-600 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1 ml-2"
              type="button"
            >
              <i class="fab fa-facebook"></i></button
            >
            <button
              class="bg-gray-800 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1 ml-2"
              type="button"
            >
              <i class="fab fa-instagram"></i>
            </button>
          </div>
        </div>
        <div class="w-full lg:w-2/12 px-4">
          <div class="flex flex-wrap items-top mb-6">
            <div class="w-full lg:w-12/12 px-4 ml-auto">
              <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3485.3666476062203!2d-110.96318174918886!3d29.124374168313082!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x86ce868ddd98f15b%3A0xee966116524ee408!2sG3%20Ingenier%C3%ADa!5e0!3m2!1ses-419!2smx!4v1601421193598!5m2!1ses-419!2smx" width="600" height="450" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
            </div>
          </div>
        </div>
      </div>
      <hr class="my-6 border-gray-400" />
      <div
        class="flex flex-wrap items-center md:justify-between justify-center"
      >
        <div class="w-full md:w-5/12 px-4 mx-auto text-center">
          <div class="text-sm text-white font-semibold py-1">
            Copyright © {{ date }} by G3 Ingeniería. Todos los Derechos
            Reservados.
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  data() {
    return {
      date: new Date().getFullYear(),
    };
  },
};
</script>
