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
          id="inicio"
        >
          <img
            src="../assets/img/fondo4.png"
            style="height: 15%; width: 100%"
          />
        </div>

        <div class="relative pb-32 -mt-64" id="nosotros"></div>

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
                  <h6 class="text-xl font-semibold uppercase">
                    Misión
                  </h6>
                  <p class="mt-2 mb-4 text-gray-600 text-left">
                    Crear soluciones innovadoras garantizando calidad a través
                    de sistemas tecnológicos, personalmente altamente capacitado
                    y comprometido con la satisfacción del cliente.
                  </p>
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
                    suman más de 8 años en el mercado mexicano, específicamente
                    en sectores como el Minero, Manufacturero, Alimenticio y
                    Agroindustrial.
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
                  <h6 class="text-xl font-semibold uppercase">
                    Visión
                  </h6>
                  <p class="mt-2 mb-4 text-gray-600 text-left">
                    Ser empresa líder como proveedor de soluciones innovadoras
                    en el área minera e industrial de Sonora.
                  </p>
                </div>
              </div>
            </div>
          </div>
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

        <div class="container mx-auto px-4">
          <div class="flex flex-wrap items-center">
            <div class="w-full md:w-5/12 px-4 mr-auto ml-auto">
              <div class="flex flex-wrap justify-center mb-8">
                <div
                  class="text-gray-600 text-center inline-flex items-center justify-center w-16 h-16 shadow-lg rounded-full bg-gray-100"
                >
                  <i class="fas fa-crosshairs text-3xl"></i>
                </div>
                <div>
                  <h3 class="ml-8 text-4xl font-semibold leading-normal">
                    Nuestro Enfoque
                  </h3>
                </div>
              </div>

              <p
                class="text-xl font-light leading-relaxed mt-0 mb-4 text-gray-700 font-bold text-gray-800"
              >
                Nuestro Enfoque es el desarrollo de soluciones para minería
              </p>
              <p
                class="text-xl leading-relaxed mt-4 mb-4 text-gray-600"
              >
                Tenemos un alto compromiso con la innovación de Procesos
                industriales, sistemas para aumentar la seguridad, sistemas para
                aumentar la disponibilidad de equipos y altamente comprometidos
                con el medio ambiente
              </p>
            </div>
            <div class="w-full md:w-4/12 px-4 mr-auto ml-auto">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg bg-red-600"
              >
                <img
                  alt="..."
                  src="../assets/img/imagen1.jpeg"
                  class="w-full align-middle rounded-lg"
                />
                
              </div>
            </div>
          </div>
        </div>

        <div class="container mx-auto px-4">
          <div class="flex flex-wrap items-center mt-4">
            <div class="w-full md:w-4/12 px-4 mr-auto ml-auto">
              <div
                class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg bg-red-600"
              >
                <img
                  alt="..."
                  src="../assets/img/imagen2.jpeg"
                  class="w-full align-middle rounded-lg"
                />
              </div>
            </div>
            <div class="w-full md:w-5/12 px-4 mr-auto ml-auto">
              <div class="flex flex-wrap justify-center mb-8">
                <div
                  class="text-gray-600 text-center inline-flex items-center justify-center w-16 h-16 shadow-lg rounded-full bg-gray-100"
                >
                  <i class="fas fa-balance-scale text-3xl"></i>
                </div>
                <div>
                  <h3 class="ml-8 text-4xl font-semibold leading-normal">
                    Nuestros Valores
                  </h3>
                </div>
              </div>

              <div class="flex flex-wrap" id="servicios">
                <div class="mr-auto ml-4">
                  <ul class="text-xl lg:mt-2 lg:mb-4 text-gray-600 list-disc">
                    <li>Pasión por lo que hacemos</li>
                    <li>Confianza y Respeto</li>
                    <li>Innovación</li>
                    <li>Compromiso</li>
                    <li>Superación</li>
                  </ul>
                </div>
                <div class="mr-auto ml-4">
                  <ul class="text-xl lg:mt-2 lg:mb-4 text-gray-600 list-disc">
                    <li>Trabajo en Equipo</li>
                    <li>Lealtad</li>
                    <li>Integridad</li>
                    <li>Actitud de Servicio</li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="container mx-auto mt-4">
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
                  <div
                    class="flex flex-wrap w-10/12 text-xl justify-center self-center text-left"
                  >
                    <ul class="ml-8 mt-2 mb-4 text-white list-disc">
                      <li>
                        Desarrollo de Software para Control y Monitoreo de
                        Sistemas.
                      </li>
                      <li>
                        Banco Horas Hombre (HH) para programación PLC's y/o
                        HMI's.
                      </li>
                      <li>
                        Desarrollo de enlaces de comunicación inalámbrica para
                        monitoreo y control de sistemas. (Telemetría)
                      </li>
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
                  <h6 class="text-3xl text-white  font-semibold">
                    Instalación
                  </h6>
                  <div
                    class="flex flex-wrap w-10/12 justify-center self-center text-left text-xl"
                  >
                    <ul class="ml-8 mt-2 mb-4 text-white list-disc">
                      <li>
                        Suministro, instalación y comisionamiento de
                        instrumentación de proceso y/o válvulas de control.
                      </li>
                      <li>
                        Ingeniería, reingeniería y armado de tableros de control
                        y potencia.
                      </li>
                      <li>
                        Pólizas de mantenimiento a sistemas de control e
                        instrumentación.
                      </li>
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
                  <div
                    class="flex flex-wrap w-10/12 justify-center self-center text-left text-xl"
                  >
                    <ul class="ml-8 mt-2 mb-4 text-white list-disc">
                      <li>Ingeniería y diseño de redes de control.</li>
                      <li>Integración de sistemas de control de acceso.</li>
                      <li>Sistemas de Respaldo de energía.</li>
                      <li>Sistemas de energía solar.</li>
                      <li>
                        Suministro, instalación y comisionamiento de variadores
                        de velocidad.
                      </li>
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
          <div
            class="flex flex-wrap justify-center text-center mb-12"
            id="clientes"
          >
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
            <div class="w-full mb-12">
              <flickity
                class="flickity"
                ref="flickity"
                :options="flickityOptions"
              >
                  <img
                    class="carousel-image"
                    alt="Norson"
                    src="../assets/img/norson1.png"
                    style="width: 300px; height: 200px; margin-right: 10px; display: block;"
                  />

                  <img
                    alt="Peñoles"
                    src="../assets/img/penioles.png"
                    class="carousel-image"
                    style="width: 300px; height: 200px; margin-right: 10px; display: block;"
                  />

                  <img
                    alt="Grupo México"
                    src="../assets/img/cobreDelMayo1.png"
                    class="carousel-image"
                    style="width: 300px; height: 200px; margin-right: 10px; display: block;"
                  />

                  <img
                    alt="Norson"
                    src="../assets/img/fresnilloPLC.png"
                    class="carousel-image"
                    style="width: 300px; height: 200px; margin-right: 10px; display: block;"
                  />

                  <img
                    alt="Peñoles"
                    src="../assets/img/grupoMexico2.png"
                    class="carousel-image"
                    style="width: 300px; height: 200px; margin-right: 10px; display: block;"
                  />

                  <img
                    alt="Metallorum"
                    src="../assets/img/Metallorum2.png"
                    class="carousel-image"
                    style="width: 300px; height: 200px; margin-right: 10px; display: block;"
                  />
                
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
        "autoPlay": 1500,
        "pageDots": true,
        "resize": true,
        "prevNextButtons": true,
        "wrapAround": true,
        "freeScroll": true,
        "contain": false,
        "pauseAutoPlayOnHover": false,
        "adaptiveHeight": true,
        "imagesLoaded": true
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
