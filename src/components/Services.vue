<template>
  <section id="servicios" class="bg-gray-100 py-24 sm:py-32">
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <!-- Encabezado -->
      <div class="mx-auto max-w-3xl text-center">
        <p
          class="text-sm font-semibold uppercase tracking-[0.3em] text-gray-500"
        >
          Membresías CONCRETA
        </p>

        <h2
          class="mt-4 text-4xl font-bold tracking-tight text-gray-900 sm:text-5xl"
        >
          Mantenimiento sin preocupaciones.
        </h2>

        <p class="mt-6 text-lg leading-8 text-gray-600">
          Elegí la membresía que mejor se adapta a tu propiedad y nosotros nos
          ocupamos del mantenimiento.
        </p>
      </div>

      <!-- Membresías -->
      <div
        class="mx-auto mt-16 grid max-w-6xl gap-8 lg:grid-cols-3 lg:items-stretch"
      >
        <!-- BÁSICO -->
        <article
          class="relative flex flex-col rounded-2xl bg-white p-8 shadow-sm ring-1 ring-gray-200 transition duration-300 hover:-translate-y-2 hover:shadow-xl"
        >
          <div>
            <p
              class="text-sm font-semibold uppercase tracking-widest text-gray-500"
            >
              Membresía
            </p>

            <h3 class="mt-2 text-3xl font-bold text-gray-900">Básico</h3>

            <div class="mt-4">
              <span class="text-4xl font-bold text-gray-900">$35.000</span>
              <span class="ml-2 text-sm text-gray-500">por mes</span>
            </div>

            <p class="mt-4 text-sm leading-6 text-gray-600">
              La opción ideal para mantener tu propiedad en buenas condiciones
              durante todo el año.
            </p>
          </div>

          <div class="my-8 h-px bg-gray-200"></div>

          <ul class="space-y-4">
            <li
              v-for="item in basico"
              :key="item"
              class="flex items-start gap-3"
            >
              <span
                class="mt-0.5 flex h-5 w-5 shrink-0 items-center justify-center rounded-full bg-gray-900 text-xs text-white"
              >
                ✓
              </span>

              <span class="text-sm text-gray-700">
                {{ item }}
              </span>
            </li>
          </ul>

          <div class="mt-auto pt-8">
            <a
              :href="whatsappLink"
              target="_blank"
              rel="noopener noreferrer"
              class="block rounded-lg border border-gray-900 px-5 py-3 text-center text-sm font-semibold text-gray-900 transition hover:bg-gray-900 hover:text-white"
            >
              Consultar membresía
            </a>
          </div>
        </article>

        <!-- PREMIUM -->
        <article
          class="relative flex flex-col rounded-2xl bg-gray-900 p-8 text-white shadow-xl transition duration-300 hover:-translate-y-2"
        >
          <!-- Etiqueta -->
          <div
            class="absolute -top-4 left-1/2 -translate-x-1/2 rounded-full bg-white px-5 py-1.5 text-xs font-bold uppercase tracking-wider text-gray-900 shadow-md"
          >
            Más elegida
          </div>

          <div>
            <p
              class="text-sm font-semibold uppercase tracking-widest text-gray-400"
            >
              Membresía
            </p>

            <h3 class="mt-2 text-3xl font-bold">Premium</h3>

            <div class="mt-4">
              <span class="text-4xl font-bold text-white">$50.000</span>
              <span class="ml-2 text-sm text-gray-400">por mes</span>
            </div>

            <p class="mt-4 text-sm leading-6 text-gray-300">
              Mayor cobertura para quienes buscan tener su propiedad siempre
              lista y cuidada.
            </p>
          </div>

          <div class="my-8 h-px bg-white/20"></div>

          <ul class="space-y-4">
            <li
              v-for="item in premium"
              :key="item"
              class="flex items-start gap-3"
            >
              <span
                class="mt-0.5 flex h-5 w-5 shrink-0 items-center justify-center rounded-full bg-white text-xs text-gray-900"
              >
                ✓
              </span>

              <span class="text-sm text-gray-200">
                {{ item }}
              </span>
            </li>
          </ul>

          <div class="mt-auto pt-8">
            <a
              :href="whatsappLink"
              target="_blank"
              rel="noopener noreferrer"
              class="block rounded-lg bg-white px-5 py-3 text-center text-sm font-semibold text-gray-900 transition hover:bg-gray-200"
            >
              Consultar membresía
            </a>
          </div>
        </article>

        <!-- COMERCIAL -->
        <article
          class="relative flex flex-col rounded-2xl bg-white p-8 shadow-sm ring-1 ring-gray-200 transition duration-300 hover:-translate-y-2 hover:shadow-xl"
        >
          <div>
            <p
              class="text-sm font-semibold uppercase tracking-widest text-gray-500"
            >
              Membresía
            </p>

            <h3 class="mt-2 text-3xl font-bold text-gray-900">Comercial</h3>

            <div class="mt-4">
              <span class="text-4xl font-bold text-gray-900">$70.000</span>
              <span class="ml-2 text-sm text-gray-500">por mes</span>
            </div>

            <p class="mt-4 text-sm leading-6 text-gray-600">
              Pensada para comercios y propiedades que necesitan mantenimiento
              continuo y preventivo.
            </p>
          </div>

          <div class="my-8 h-px bg-gray-200"></div>

          <ul class="space-y-4">
            <li
              v-for="item in comercial"
              :key="item"
              class="flex items-start gap-3"
            >
              <span
                class="mt-0.5 flex h-5 w-5 shrink-0 items-center justify-center rounded-full bg-gray-900 text-xs text-white"
              >
                ✓
              </span>

              <span class="text-sm text-gray-700">
                {{ item }}
              </span>
            </li>
          </ul>

          <div class="mt-auto pt-8">
            <a
              :href="whatsappLink"
              target="_blank"
              rel="noopener noreferrer"
              class="block rounded-lg border border-gray-900 px-5 py-3 text-center text-sm font-semibold text-gray-900 transition hover:bg-gray-900 hover:text-white"
            >
              Consultar membresía
            </a>
          </div>
        </article>
      </div>

      <!-- CTA -->
      <div
        class="mx-auto mt-16 max-w-6xl overflow-hidden rounded-3xl bg-gray-900 px-8 py-12 text-center shadow-xl sm:px-12 sm:py-16"
      >
        <p
          class="text-sm font-semibold uppercase tracking-[0.25em] text-gray-400"
        >
          ¿Necesitás ayuda para elegir?
        </p>

        <h3
          class="mx-auto mt-4 max-w-3xl text-3xl font-bold tracking-tight text-white sm:text-4xl"
        >
          ¿No sabés qué membresía necesitás?
        </h3>

        <p
          class="mx-auto mt-5 max-w-2xl text-base leading-7 text-gray-300 sm:text-lg"
        >
          Contanos qué tipo de propiedad tenés y qué necesidades de
          mantenimiento presenta. Te ayudamos a encontrar el plan
          <strong class="font-bold text-white">CONCRETA</strong>
          adecuado para vos.
        </p>

        <div class="mt-8">
          <a
            :href="whatsappLink"
            target="_blank"
            rel="noopener noreferrer"
            class="inline-flex items-center justify-center rounded-lg bg-white px-7 py-3.5 text-sm font-bold text-gray-900 shadow-sm transition hover:bg-gray-200"
          >
            Quiero mi Membresía Concreta
          </a>
        </div>
      </div>
    </div>
    ```
  </section>
</template>

<script setup>
const whatsappNumber = "5493810000000";

const whatsappMessage = encodeURIComponent(
  "Hola, quiero consultar por las Membresías CONCRETA. Me gustaría recibir asesoramiento para elegir la membresía adecuada.",
);

const whatsappLink = `https://wa.me/${whatsappNumber}?text=${whatsappMessage}`;

const basico = [
  "Albañilería",
  "Pintura",
  "Electricidad",
  "Gasista",
  "Abono mensual",
];

const premium = [
  "Albañilería",
  "Pintura",
  "Electricidad",
  "Gasista",
  "Limpieza de canaletas",
  "Poda / Mantenimiento de césped",
  "Atención 24 hs.",
  "Abono mensual",
];

const comercial = [
  "Albañilería",
  "Pintura",
  "Electricidad",
  "Gasista",
  "Limpieza de canaletas",
  "Poda / Mantenimiento de césped",
  "Atención 24 hs.",
  "Mantenimiento preventivo",
  "Abono mensual",
];
</script>
