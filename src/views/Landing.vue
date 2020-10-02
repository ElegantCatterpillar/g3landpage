<template>
  <div>
    <div
      style="position: fixed; 
      top: -50%; 
      left: -50%; 
      width: 200%; 
      height: 200%;"
    >
      <img
        style="position: fixed; 
        top: 0; 
        left: 0; 
        right: 0; 
        bottom: 0; 
        min-width: 50%;
        min-height: 50%;"
        src="../assets/img/backgrundImage3.png"
      />
    </div>
    <navbar-component></navbar-component>
    <main>
      
      <section class="pb-20 relative block bg-gray-300">
        <div
        class="relative pt-24 pb-16 flex content-center items-center justify-center"
        >
        <img src="../assets/img/fondo4.png">
      </div>
        <div class="container mx-auto px-4">
          <div class="flex flex-wrap">
            <div class="lg:pt-12 pt-6 w-full md:w-4/12 px-4 text-center">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
              >
                <div class="px-4 py-5 flex-auto">
                  <img
                    alt="..."
                    src="../assets/img/Nosotros.svg"
                    class="max-w-full mx-auto mb-3"
                    style="max-width: 120px;"
                  />
                  <h6 class="text-xl font-semibold uppercase">Nuestros Valores</h6>
                  <div class="flex flex-wrap justify-center text-left">
                    <ul class="ml-8 mt-2 mb-4 text-gray-600 list-disc">
                      <li>Pasión por lo que hacemos</li>
                      <li>Confianza y Respeto</li>
                      <li>Trabajo en Equipo</li>
                      <li>Lealtad</li>
                      <li>Integridad</li>
                      <li>Actitud de Servicio</li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
            <div class="w-full md:w-4/12 px-4 text-center">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
              >
                <div class="px-4 py-5 flex-auto">
                  <img
                    alt="..."
                    src="../assets/img/Nosotros.svg"
                    class="max-w-full mx-auto mb-3"
                    style="max-width: 120px;"
                  />
                  <h6 class="text-xl font-semibold uppercase">Nosotros</h6>
                  <p class="mt-2 mb-4 text-gray-600 text-left">
                    Somos un grupo de ingenieros cuya
                    <strong class="font-semibold"
                      >experiencia en el área de desarrollo de proyectos y
                      servicios de automatización, control e instrumentación
                    </strong>
                    suman más de 8 años en el mercado mexicano, especificamente en
                    sectores como el Minero, Manufacturero, Alimenticio y
                    Agroindustrial.
                  </p>
                  <p class="mt-2 mb-4 text-gray-600 text-left">
                    Nuestra empresa nace comercialmente en el año 2017, ubicándose
                    en Hermosillo, Sonora.
                  </p>
                </div>
              </div>
            </div>
            <div class="pt-6 w-full md:w-4/12 px-4 text-center">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
              >
                <div class="px-4 py-5 flex-auto">
                  <img
                    alt="..."
                    src="../assets/img/Enfoque.svg"
                    class="max-w-full mx-auto mb-3"
                    style="max-width: 120px;"
                  />
                  <h6 class="text-xl font-semibold uppercase">Nuestro Enfoque</h6>
                  <p class="mt-2 mb-4 text-gray-600 text-left">
                    Tenemos un alto compromiso con la innovación de Procesos
                    industriales, sistemas para aumentar la seguridad, sistemas
                    para aumentar la disponibilidad de equipos y altamente
                    comprometidos con el medio ambiente
                  </p>
                </div>
              </div>
            </div>
          </div>

          <!--
          <div class="flex flex-wrap items-center mt-32">
            <div class="w-full md:w-5/12 px-4 mr-auto ml-auto">
              <div
                class="text-gray-600 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-gray-100"
              >
                <i class="fas fa-users text-xl"></i>
              </div>
              <h3 class="text-3xl mb-2 font-semibold leading-normal">
                Nosotros
              </h3>
              <p
                class="text-lg font-light leading-relaxed mt-4 mb-4 text-gray-700"
              >
                Somos un grupo de ingenieros cuya
                <strong class="font-bold"
                  >experiencia en el área de desarrollo de proyectos y servicios
                  de automatización, control e instrumentación
                </strong>
                suman más de 8 años en el mercado mexicano, especificamente en
                sectores como el Minero, Manufacturero, Alimenticio y
                Agroindustrial.
              </p>
              <p
                class="text-lg font-light leading-relaxed mt-0 mb-4 text-gray-700"
              >
                Nuestra empresa nace comercialmente en el año 2017, ubicándose
                en Hermosillo, Sonora.
              </p>
              <a
                href="https://www.creative-tim.com/learning-lab/tailwind-starter-kit#/presentation"
                class="font-bold text-gray-800 mt-8"
                >Check Tailwind Starter Kit!</a
              >
            </div>
            <div class="w-full md:w-4/12 px-4 mr-auto ml-auto">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg bg-red-600"
              >
                <img
                  alt="..."
                  src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=crop&amp;w=1051&amp;q=80"
                  class="w-full align-middle rounded-t-lg"
                />
                <blockquote class="relative p-8 mb-4">
                  <svg
                    preserveAspectRatio="none"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 583 95"
                    class="absolute left-0 w-full block"
                    style="height: 95px; top: -94px;"
                  >
                    <polygon
                      points="-30,95 583,95 583,65"
                      class="text-red-600 fill-current"
                    ></polygon>
                  </svg>
                  <h4 class="text-xl font-bold text-white">
                    Top Notch Services
                  </h4>
                  <p class="text-md font-light mt-2 text-white">
                    The Arctic Ocean freezes every winter and much of the
                    sea-ice then thaws every summer, and that process will
                    continue whatever happens.
                  </p>
                </blockquote>
              </div>
            </div>
          </div>
          -->

        </div>
      </section>

      <section class="relative block pt-20">
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
              class="text-white fill-current"
              points="2560 0 2560 100 0 100"
            ></polygon>
          </svg>
        </div>
        <div class="container mx-auto">
          <div class="flex flex-wrap justify-center text-center">
            <div class="w-full lg:w-12/12">
              <h2 class="text-5xl font-semibold">
                Servicios
              </h2>
            </div>
          </div>
          <div class="flex flex-wrap">
            <div class="lg:pt-12 pt-6 w-full md:w-4/12 px-4 text-center">
              <div
                class="relative flex flex-col min-w-0 break-words w-full mb-8 shadow-lg rounded-lg bg-red-600"
              >
                <div class="px-4 py-5 flex-auto">
                  <div
                    class="text-red-600 text-4xl p-3 text-center inline-flex items-center w-32 h-32 justify-center mb-3 shadow-lg rounded-full bg-white"
                  >
                    <i class="fas fa-code"></i>
                  </div>
                  <h6 class="text-3xl text-white font-semibold">Desarrollo</h6>
                  <div class="flex flex-wrap w-10/12 text-xl justify-center self-center text-left">
                    <ul class="ml-8 mt-2 mb-4 text-white list-disc">
                      <li>Desarrollo de Software para Control y Monitoreo de Sistemas.</li>
                      <li>Banco Horas Hombre (HH) para programación PLC's y/o HMI's.</li>
                      <li>Desarrollo de enlaces de comunicación inalámbrica para monitoreo y control de sistemas. (Telemetría)</li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
            <div class="w-full lg:pt-12 pt-6 md:w-4/12 px-4 text-center">
              <div
                class="relative flex flex-col min-w-0 break-words w-full mb-8 shadow-lg rounded-lg bg-red-600"
              >
                <div class="px-4 py-5 flex-auto">
                  <div
                    class="text-red-600 text-4xl p-3 text-center inline-flex items-center w-32 h-32 justify-center mb-3 shadow-lg rounded-full bg-white"
                  >
                    <i class="fas fa-tools"></i>
                  </div>
                  <h6 class="text-3xl text-white  font-semibold">Instalación</h6>
                  <div class="flex flex-wrap w-10/12 justify-center self-center text-left text-xl">
                    <ul class="ml-8 mt-2 mb-4 text-white list-disc">
                      <li>Suministro, instalación y comisionamiento de instrumentación de proceso y/o válvulas de control.</li>
                      <li>Ingeniería, reingeniería y armado de tableros de control y potencia.</li>
                      <li>Pólizas de mantenimiento a sistemas de control e instrumentación.</li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
            <div class="pt-6 lg:pt-12 w-full md:w-4/12 px-4 text-center">
              <div
                class="relative flex flex-col min-w-0 break-words w-full mb-8 shadow-lg rounded-lg bg-red-600"
              >
                <div class="px-4 py-5 flex-auto">
                  <div
                    class="text-red-600 text-4xl p-3 text-center inline-flex items-center w-32 h-32 justify-center mb-3 shadow-lg rounded-full bg-white"
                  >
                    <i class="fas fa-brain"></i>
                  </div>
                  <h6 class="text-3xl text-white font-semibold">Ingeniería</h6>
                  <div class="flex flex-wrap w-10/12 justify-center self-center text-left text-xl">
                    <ul class="ml-8 mt-2 mb-4 text-white list-disc">
                      <li>Ingeniería y diseño de redes de control.</li>
                      <li>Integración de sistemas de control de acceso.</li>
                      <li>Sistemas de Respaldo de energía.</li>
                      <li>Sistemas de energía solar.</li>
                      <li>Suministro, instalación y comisionamiento de variadores de velocidad.</li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="relative block pt-20 pb-32">
        <div class="container mx-auto">
          <div class="flex flex-wrap justify-center text-center">
            <div class="w-full lg:w-12/12">
              <h2 class="text-5xl font-semibold">
                Proyectos y Servicios que ayudan a mejorar
              </h2>
            </div>
          </div>
          <div class="flex flex-wrap justify-center text-center mb-12">
            <div class="flex flex-wrap mt-12 pt-12">
              <div class="w-full md:w-4/12 lg:w-4/12 lg:mb-0 mb-12 px-4">
                <div class="px-6">
                  <img
                    alt="..."
                    src="../assets/img/servicio2.svg"
                    class="max-w-full mx-auto"
                    style="max-width: 120px;"
                  />
                  <div class="pt-6 text-center">
                    <h5 class="text-xl text-gray-700 font-bold">
                      Control de Procesos
                    </h5>
                  </div>
                </div>
              </div>
              <div class="w-full md:w-4/12 lg:w-4/12 lg:mb-0 mb-12 px-4">
                <div class="px-6">
                  <img
                    alt="..."
                    src="../assets/img/servicio3.svg"
                    class="max-w-full mx-auto"
                    style="max-width: 120px;"
                  />
                  <div class="pt-6 text-center">
                    <h5 class="text-xl text-gray-700 font-bold">
                      Seguridad y Ecología
                    </h5>
                  </div>
                </div>
              </div>
              <div class="w-full md:w-4/12 lg:w-4/12 lg:mb-0 mb-12 px-4">
                <div class="px-6">
                  <img
                    alt="..."
                    src="../assets/img/servicio1.svg"
                    class="max-w-full mx-auto"
                    style="max-width: 120px;"
                  />
                  <div class="pt-6 text-center">
                    <h5 class="text-xl text-gray-700 font-bold">
                      Control Administrativo
                    </h5>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="mb-12">
            <hr style="border-color: #E53E3E; border-bottom-style: solid;" />
            <hr style="border-color: #E53E3E; border-bottom-style: solid;" />
          </div>
          <div class="flex flex-wrap justify-center text-center mb-12">
            <div class="w-full lg:w-6/12">
              <h2 class="text-4xl font-semibold">Nuestros Clientes</h2>
            </div>
          </div>

          <div class="flex flex-wrap">
            <div class="w-full mb-12 px-4">
              <flickity
                class="flickity"
                ref="flickity"
                :options="flickityOptions"
              >
                <div class="carousel-cell">
                  <img
                    alt="Grupo México"
                    src="../assets/img/cliente1.png"
                    class="max-w-full mx-auto"
                    style="max-width: 300px;"
                  />
                </div>

                <div class="carousel-cell">
                  <img
                    alt="Norson"
                    src="../assets/img/cliente2.png"
                    class="max-w-full mx-auto"
                    style="max-width: 450px;"
                  />
                </div>

                <div class="carousel-cell">
                  <img
                    alt="Peñoles"
                    src="../assets/img/cliente3.png"
                    class="max-w-full mx-auto"
                    style="max-width: 300px;"
                  />
                </div>

                <div class="carousel-cell">
                  <img
                    alt="Cobre del Mayo"
                    src="../assets/img/cliente4.png"
                    class="max-w-full mx-auto mt-10"
                    style="max-width: 300px;"
                  />
                </div>

                <div class="carousel-cell">
                  <img
                    alt="Fresnillo"
                    src="../assets/img/cliente5.png"
                    class="max-w-full mx-auto"
                    style="max-width: 450px;"
                  />
                </div>
              </flickity>
            </div>
          </div>
        </div>
      </section>

      <section class="pb-40 relative block bg-gray-700">
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
              class="text-gray-700 fill-current"
              points="2560 0 2560 100 0 100"
            ></polygon>
          </svg>
        </div>
        <div class="container mx-auto px-4 lg:py-4 pt-4">
          <div class="flex flex-wrap text-center justify-center">
            <div class="w-full lg:w-6/12 px-4">
              <h2 class="text-4xl font-semibold text-white hidden">
                ¿Quieres trabajar con nosotros?
              </h2>
            </div>
          </div>
        </div>
      </section>

      <section class="relative block py-24 lg:pt-3 bg-gray-700">
        <div class="container mx-auto px-4">
          <div class="flex flex-wrap justify-center -mt-48">
            <div class="w-full lg:w-8/12 px-4">
              <div
                class="relative flex flex-col min-w-0 break-words w-full mb-6 shadow-lg rounded-lg bg-gray-300"
              >
                <div class="flex-auto p-5 lg:p-10">
                  <form class="contact-form" @submit.prevent="sendEmail">
                    <h4 class="text-4xl text-center font-semibold">
                      ¡Comunícate con Nosotros!
                    </h4>
                    <p
                      class="text-center leading-relaxed mt-1 mb-4 text-gray-900"
                    >
                      ¡Complete el siguiente formulario y nos comunicaremos con
                      usted!
                    </p>
                    <div class="relative w-full mb-3 mt-8">
                      <label
                        class="block uppercase text-gray-700 text-xs font-bold mb-2"
                        for="full-name"
                        >Nombre y Apellido</label
                      ><input
                        type="text"
                        required
                        pattern="^[a-zA-Z]+( [a-zA-Z]+)+$"
                        oninvalid="this.setCustomValidity('Ingresa el nombre con el cuál te llamaremos - Nombre + Apellido')"
                        oninput="this.setCustomValidity('')"
                        class="px-3 py-3 placeholder-gray-400 text-gray-700 bg-white rounded text-sm shadow focus:outline-none focus:shadow-outline w-full"
                        placeholder="Nombre y Apellido"
                        name="user_name"
                        style="transition: all 0.15s ease 0s;"
                      />
                    </div>
                    <div class="relative w-full mb-3">
                      <label
                        class="block uppercase text-gray-700 text-xs font-bold mb-2"
                        for="user_number"
                        >Número de Contacto</label
                      ><input
                        type="tel"
                        pattern="[0-9]{9,14}"
                        oninvalid="this.setCustomValidity('Ingresa Un Número Telefonico Completo (LADA OPCIONAL + 10 Dígitos)')"
                        oninput="this.setCustomValidity('')"
                        required
                        class="px-3 py-3 placeholder-gray-400 text-gray-700 bg-white rounded text-sm shadow focus:outline-none focus:shadow-outline w-full"
                        placeholder="Número de Contacto"
                        name="user_number"
                        style="transition: all 0.15s ease 0s;"
                      />
                    </div>
                    <div class="relative w-full mb-3">
                      <label
                        class="block uppercase text-gray-700 text-xs font-bold mb-2"
                        for="email"
                        >Correo Electronico</label
                      ><input
                        type="email"
                        required
                        pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,4}$"
                        oninvalid="this.setCustomValidity('Ingresa una Dirección de Correo Completa')"
                        oninput="this.setCustomValidity('Ingrese una Dirección de Correo Válida (correo@ejemplo.com)')"
                        class="px-3 py-3 placeholder-gray-400 text-gray-700 bg-white rounded text-sm shadow focus:outline-none focus:shadow-outline w-full"
                        placeholder="Correo Electronico"
                        name="user_email"
                        style="transition: all 0.15s ease 0s;"
                      />
                    </div>
                    <div class="relative w-full mb-3">
                      <label
                        class="block uppercase text-gray-700 text-xs font-bold mb-2"
                        for="message"
                        >Mensaje</label
                      ><textarea
                        rows="4"
                        cols="80"
                        name="message"
                        required
                        oninvalid="this.setCustomValidity('Ingresa un Mensaje')"
                        oninput="this.setCustomValidity('')"
                        class="px-3 py-3 placeholder-gray-400 text-gray-700 bg-white rounded text-sm shadow focus:outline-none focus:shadow-outline w-full"
                        placeholder="Escribe un mensaje..."
                      ></textarea>
                    </div>
                    <div class="text-center mt-6">
                      <button
                        class="bg-gray-900 text-white active:bg-gray-700 text-sm font-bold uppercase px-6 py-3 rounded shadow hover:shadow-lg outline-none focus:outline-none mr-1 mb-1"
                        type="submit"
                        value="Send"
                        style="transition: all 0.15s ease 0s;"
                      >
                        Enviar Mensaje
                      </button>
                    </div>
                  </form>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
    <footer-component></footer-component>
  </div>
</template>

<script>
import emailjs from "emailjs-com";
import Flickity from "vue-flickity";
import NavbarComponent from "../components/Navbar.vue";
import FooterComponent from "../components/Footer.vue";
export default {
  name: "landing-page",
  components: {
    NavbarComponent,
    FooterComponent,
    Flickity,
  },
  data() {
    return {
      flickityOptions: {
        autoPlay: 1500,
        initialIndex: 2,
        prevNextButtons: true,
        pageDots: false,
        wrapAround: true,
        freeScroll: true,
        // any options from Flickity can be used
      },
    };
  },
  methods: {
    sendEmail: (e) => {
      emailjs
        .sendForm(
          "service_9lsyuu7",
          "template_p919xwc",
          e.target,
          "user_keASSjIf2Xc4RyEVyXLfY"
        )
        .then(
          (result) => {
            alert("Mensaje Enviado! - " + result.text);
          },
          (error) => {
            alert("Error al Enviar Mensaje! - " + error.headers);
          }
        );
    },
  },
};
</script>
