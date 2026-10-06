<template>
  <section id="contacto" class="bg-gray-100 py-24 sm:py-32">
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <!-- Encabezado -->
      <div class="mx-auto max-w-3xl text-center">
        <p
          class="text-sm font-semibold uppercase tracking-[0.3em] text-gray-500"
        >
          Contacto
        </p>

        <h2
          class="mt-4 text-4xl font-bold tracking-tight text-gray-900 sm:text-5xl"
        >
          Hablemos de tu proyecto.
        </h2>

        <p class="mt-6 text-lg leading-8 text-gray-600">
          Contanos qué necesitás y nos pondremos en contacto para ayudarte a
          encontrar la mejor solución.
        </p>
      </div>

      <!-- Contenido -->
      <div class="mx-auto mt-16 grid max-w-6xl gap-10 lg:grid-cols-2">
        <!-- Información -->
        <div class="rounded-2xl bg-gray-900 p-8 text-white shadow-xl sm:p-10">
          <p
            class="text-sm font-semibold uppercase tracking-[0.25em] text-gray-400"
          >
            Estamos para ayudarte
          </p>

          <h3 class="mt-4 text-3xl font-bold">
            Ponete en contacto con nosotros.
          </h3>

          <p class="mt-5 leading-7 text-gray-300">
            Ya sea que estés pensando en construir, remodelar o necesites
            mantenimiento para tu propiedad, estamos listos para asesorarte.
          </p>

          <!-- Datos -->
          <div class="mt-10 space-y-7">
            <!-- WhatsApp -->
            <div class="flex gap-4">
              <div
                class="flex h-11 w-11 shrink-0 items-center justify-center rounded-lg bg-white/10"
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
              </div>

              <div>
                <p class="text-sm text-gray-400">WhatsApp</p>

                <a
                  :href="whatsappLink"
                  target="_blank"
                  rel="noopener noreferrer"
                  class="mt-1 block font-medium transition hover:text-gray-300"
                >
                  Escribinos por WhatsApp
                </a>
              </div>
            </div>

            <!-- Teléfono -->
            <div class="flex gap-4">
              <div
                class="flex h-11 w-11 shrink-0 items-center justify-center rounded-lg bg-white/10"
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
                    d="M3 5a2 2 0 012-2h3.28a2 2 0 011.94 1.515L11 8a2 2 0 01-.5 1.83l-1.2 1.2a16 16 0 006.67 6.67l1.2-1.2a2 2 0 011.83-.5l3.485.78A2 2 0 0124 18.72V22a2 2 0 01-2 2h-1C10.61 24 0 13.39 0 0V0"
                  />
                </svg>
              </div>

              <div>
                <p class="text-sm text-gray-400">Teléfono</p>

                <p class="mt-1 font-medium">+54 381 XXX XXXX</p>
              </div>
            </div>

            <!-- Email -->
            <div class="flex gap-4">
              <div
                class="flex h-11 w-11 shrink-0 items-center justify-center rounded-lg bg-white/10"
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
                    d="M3 7l9 6 9-6M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
                  />
                </svg>
              </div>

              <div>
                <p class="text-sm text-gray-400">Email</p>

                <p class="mt-1 font-medium">contacto@constructora.com</p>
              </div>
            </div>

            <!-- Ubicación -->
            <div class="flex gap-4">
              <div
                class="flex h-11 w-11 shrink-0 items-center justify-center rounded-lg bg-white/10"
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
                    d="M12 21s7-5.5 7-12a7 7 0 10-14 0c0 6.5 7 12 7 12z"
                  />
                  <circle cx="12" cy="9" r="2.5" />
                </svg>
              </div>

              <div>
                <p class="text-sm text-gray-400">Ubicación</p>

                <p class="mt-1 font-medium">San Miguel de Tucumán, Tucumán</p>
              </div>
            </div>
          </div>

          <!-- WhatsApp -->
          <a
            :href="whatsappLink"
            target="_blank"
            rel="noopener noreferrer"
            class="mt-10 inline-flex w-full items-center justify-center rounded-lg bg-white px-6 py-3.5 text-sm font-bold text-gray-900 transition hover:bg-gray-200"
          >
            Contactar por WhatsApp
          </a>
        </div>

        <!-- Formulario -->
        <div
          class="rounded-2xl bg-white p-8 shadow-sm ring-1 ring-gray-200 sm:p-10"
        >
          <h3 class="text-2xl font-bold text-gray-900">Solicitar consulta</h3>

          <p class="mt-2 text-sm leading-6 text-gray-600">
            Completá el formulario y nos pondremos en contacto con vos.
          </p>

          <form class="mt-8 space-y-6">
            <!-- Nombre -->
            <div>
              <label
                for="nombre"
                class="block text-sm font-medium text-gray-900"
              >
                Nombre
              </label>

              <input
                id="nombre"
                type="text"
                placeholder="Tu nombre"
                class="mt-2 block w-full rounded-lg border border-gray-300 px-4 py-3 text-sm text-gray-900 outline-none transition placeholder:text-gray-400 focus:border-gray-900 focus:ring-1 focus:ring-gray-900"
              />
            </div>

            <!-- Email -->
            <div>
              <label
                for="email"
                class="block text-sm font-medium text-gray-900"
              >
                Email
              </label>

              <input
                id="email"
                type="email"
                placeholder="tu@email.com"
                class="mt-2 block w-full rounded-lg border border-gray-300 px-4 py-3 text-sm text-gray-900 outline-none transition placeholder:text-gray-400 focus:border-gray-900 focus:ring-1 focus:ring-gray-900"
              />
            </div>

            <!-- Teléfono -->
            <div>
              <label
                for="telefono"
                class="block text-sm font-medium text-gray-900"
              >
                Teléfono
              </label>

              <input
                id="telefono"
                type="tel"
                placeholder="+54 381 ..."
                class="mt-2 block w-full rounded-lg border border-gray-300 px-4 py-3 text-sm text-gray-900 outline-none transition placeholder:text-gray-400 focus:border-gray-900 focus:ring-1 focus:ring-gray-900"
              />
            </div>

            <!-- Mensaje -->
            <div>
              <label
                for="mensaje"
                class="block text-sm font-medium text-gray-900"
              >
                ¿En qué podemos ayudarte?
              </label>

              <textarea
                id="mensaje"
                rows="5"
                placeholder="Contanos brevemente sobre tu proyecto..."
                class="mt-2 block w-full resize-none rounded-lg border border-gray-300 px-4 py-3 text-sm text-gray-900 outline-none transition placeholder:text-gray-400 focus:border-gray-900 focus:ring-1 focus:ring-gray-900"
              ></textarea>
            </div>

            <!-- Botón -->
            <button
              type="submit"
              class="w-full rounded-lg bg-gray-900 px-6 py-3.5 text-sm font-semibold text-white transition hover:bg-gray-700"
            >
              Enviar consulta
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
const whatsappNumber = "5493810000000";

const whatsappMessage = encodeURIComponent(
  "Hola, quiero realizar una consulta sobre los servicios de CONCRETA.",
);

const whatsappLink = `https://wa.me/${whatsappNumber}?text=${whatsappMessage}`;
</script>
