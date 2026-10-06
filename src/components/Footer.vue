<template>
  <footer class="bg-gray-950 text-white">
    <!-- Contenido principal -->
    <div class="mx-auto max-w-7xl px-6 py-16 lg:px-8">
      <div class="grid gap-12 md:grid-cols-2 lg:grid-cols-4">
        <!-- Marca -->
        <div class="lg:col-span-2">
          <a href="#inicio" class="inline-flex items-center gap-3">
            <div
              class="flex h-10 w-10 items-center justify-center rounded-lg bg-white text-lg font-bold text-gray-950"
            >
              C
            </div>

            <span class="text-xl font-bold tracking-wide"> CONSTRUCTORA </span>
          </a>

          <p class="mt-6 max-w-md text-sm leading-7 text-gray-400">
            Construimos proyectos con compromiso, experiencia y atención en cada
            detalle. Soluciones pensadas para durar.
          </p>

          <!-- Redes -->
          <div class="mt-7 flex gap-3">
            <!-- Instagram -->
            <a
              href="#"
              aria-label="Instagram"
              class="flex h-10 w-10 items-center justify-center rounded-lg bg-white/10 transition hover:bg-white hover:text-gray-950"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-5 w-5"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                stroke-width="1.8"
              >
                <rect width="17" height="17" x="3.5" y="3.5" rx="4" />
                <circle cx="12" cy="12" r="4" />
                <circle
                  cx="17.5"
                  cy="6.5"
                  r=".8"
                  fill="currentColor"
                  stroke="none"
                />
              </svg>
            </a>

            <!-- Facebook -->
            <a
              href="#"
              aria-label="Facebook"
              class="flex h-10 w-10 items-center justify-center rounded-lg bg-white/10 transition hover:bg-white hover:text-gray-950"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-5 w-5"
                fill="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  d="M14 8h3V4.5c-.5-.1-2-.2-3.7-.2-3.7 0-6.2 2.3-6.2 6.4V13H3v4h4.1v7h4.5v-7H15l.5-4h-3.9v-2c0-1.2.3-2 2.4-2z"
                />
              </svg>
            </a>

            <!-- WhatsApp -->
            <a
              :href="whatsappLink"
              target="_blank"
              rel="noopener noreferrer"
              aria-label="WhatsApp"
              class="flex h-10 w-10 items-center justify-center rounded-lg bg-white/10 transition hover:bg-white hover:text-gray-950"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-5 w-5"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                stroke-width="1.8"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M21 11.5a8.38 8.38 0 01-9 8.5 8.4 8.4 0 01-4-.95L3 20l1.1-4.7A8.4 8.4 0 013 11.5 8.5 8.5 0 1112 20"
                />
              </svg>
            </a>
          </div>
        </div>

        <!-- Navegación -->
        <div>
          <h3 class="text-sm font-semibold uppercase tracking-wider">
            Navegación
          </h3>

          <ul class="mt-6 space-y-4">
            <li>
              <a
                href="#inicio"
                class="text-sm text-gray-400 transition hover:text-white"
              >
                Inicio
              </a>
            </li>

            <li>
              <a
                href="#nosotros"
                class="text-sm text-gray-400 transition hover:text-white"
              >
                Nosotros
              </a>
            </li>

            <li>
              <a
                href="#servicios"
                class="text-sm text-gray-400 transition hover:text-white"
              >
                Servicios
              </a>
            </li>

            <li>
              <a
                href="#obras"
                class="text-sm text-gray-400 transition hover:text-white"
              >
                Obras
              </a>
            </li>

            <li>
              <a
                href="#contacto"
                class="text-sm text-gray-400 transition hover:text-white"
              >
                Contacto
              </a>
            </li>
          </ul>
        </div>

        <!-- Contacto -->
        <div>
          <h3 class="text-sm font-semibold uppercase tracking-wider">
            Contacto
          </h3>

          <ul class="mt-6 space-y-4 text-sm text-gray-400">
            <li>San Miguel de Tucumán, Tucumán</li>

            <li>+54 381 XXX XXXX</li>

            <li>contacto@constructora.com</li>
          </ul>

          <a
            :href="whatsappLink"
            target="_blank"
            rel="noopener noreferrer"
            class="mt-7 inline-flex rounded-lg bg-white px-5 py-2.5 text-sm font-semibold text-gray-950 transition hover:bg-gray-200"
          >
            Escribinos por WhatsApp
          </a>
        </div>
      </div>
    </div>

    <!-- Copyright -->
    <div class="border-t border-white/10">
      <div
        class="mx-auto flex max-w-7xl justify-center px-6 py-6 text-center text-sm text-gray-500 lg:px-8"
      >
        <p>
          © {{ currentYear }} Diseñado y desarrollado por Di Colantonio
          Santiago. Todos los derechos reservados.
        </p>
      </div>
    </div>
  </footer>
</template>

<script setup>
const whatsappNumber = "5493810000000";

const whatsappMessage = encodeURIComponent(
  "Hola, quiero realizar una consulta sobre CONCRETA.",
);

const whatsappLink = `https://wa.me/${whatsappNumber}?text=${whatsappMessage}`;

const currentYear = new Date().getFullYear();
</script>
