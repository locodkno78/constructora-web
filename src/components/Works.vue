<template>
  <section id="obras" class="bg-white py-24 sm:py-32">
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <!-- Encabezado -->
      <div class="mx-auto max-w-3xl text-center">
        <p
          class="text-sm font-semibold uppercase tracking-[0.3em] text-gray-500"
        >
          Nuestras obras
        </p>

        <h2
          class="mt-4 text-4xl font-bold tracking-tight text-gray-900 sm:text-5xl"
        >
          Proyectos que hablan por nosotros.
        </h2>

        <p class="mt-6 text-lg leading-8 text-gray-600">
          Conocé algunos de los proyectos que desarrollamos, transformando ideas
          en espacios funcionales y duraderos.
        </p>
      </div>

      <!-- Obras -->
      <div
        class="mx-auto mt-16 grid max-w-6xl gap-8 md:grid-cols-2 lg:grid-cols-3"
      >
        <!-- Obra 1 -->
        <article
          class="group overflow-hidden rounded-2xl bg-white shadow-sm ring-1 ring-gray-200 transition duration-300 hover:-translate-y-2 hover:shadow-xl"
        >
          <div class="relative overflow-hidden">
            <img
              src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?auto=format&fit=crop&w=1200&q=85"
              alt="Vivienda residencial"
              class="h-72 w-full object-cover transition duration-500 group-hover:scale-105"
            />

            <div
              class="absolute left-4 top-4 rounded-full bg-white/95 px-4 py-2 text-xs font-semibold uppercase tracking-wider text-gray-900 shadow-sm"
            >
              Residencial
            </div>
          </div>

          <div class="p-7">
            <h3 class="text-2xl font-bold text-gray-900">
              Vivienda Residencial
            </h3>

            <p class="mt-3 text-sm leading-6 text-gray-600">
              Proyecto integral de construcción y terminación de vivienda
              residencial, pensado para combinar funcionalidad, diseño y
              confort.
            </p>

            <div
              class="mt-6 flex items-center justify-between border-t border-gray-100 pt-5"
            >
              <span class="text-sm text-gray-500"> Proyecto integral </span>

              <span
                class="text-sm font-semibold text-gray-900 transition group-hover:translate-x-1"
              >
                Ver proyecto →
              </span>
            </div>
          </div>
        </article>

        <!-- Obra 2 -->
        <article
          class="group overflow-hidden rounded-2xl bg-white shadow-sm ring-1 ring-gray-200 transition duration-300 hover:-translate-y-2 hover:shadow-xl"
        >
          <div class="relative overflow-hidden">
            <img
              src="https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=1200&q=85"
              alt="Remodelación de vivienda"
              class="h-72 w-full object-cover transition duration-500 group-hover:scale-105"
            />

            <div
              class="absolute left-4 top-4 rounded-full bg-white/95 px-4 py-2 text-xs font-semibold uppercase tracking-wider text-gray-900 shadow-sm"
            >
              Remodelación
            </div>
          </div>

          <div class="p-7">
            <h3 class="text-2xl font-bold text-gray-900">
              Remodelación Integral
            </h3>

            <p class="mt-3 text-sm leading-6 text-gray-600">
              Renovación y puesta en valor de espacios existentes, adaptándolos
              a nuevas necesidades y estilos de vida.
            </p>

            <div
              class="mt-6 flex items-center justify-between border-t border-gray-100 pt-5"
            >
              <span class="text-sm text-gray-500"> Renovación </span>

              <span
                class="text-sm font-semibold text-gray-900 transition group-hover:translate-x-1"
              >
                Ver proyecto →
              </span>
            </div>
          </div>
        </article>

        <!-- Obra 3 -->
        <article
          class="group overflow-hidden rounded-2xl bg-white shadow-sm ring-1 ring-gray-200 transition duration-300 hover:-translate-y-2 hover:shadow-xl"
        >
          <div class="relative overflow-hidden">
            <img
              src="https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?auto=format&fit=crop&w=1200&q=85"
              alt="Edificio comercial"
              class="h-72 w-full object-cover transition duration-500 group-hover:scale-105"
            />

            <div
              class="absolute left-4 top-4 rounded-full bg-white/95 px-4 py-2 text-xs font-semibold uppercase tracking-wider text-gray-900 shadow-sm"
            >
              Comercial
            </div>
          </div>

          <div class="p-7">
            <h3 class="text-2xl font-bold text-gray-900">Espacio Comercial</h3>

            <p class="mt-3 text-sm leading-6 text-gray-600">
              Desarrollo y acondicionamiento de espacios comerciales orientados
              a lograr ambientes funcionales y profesionales.
            </p>

            <div
              class="mt-6 flex items-center justify-between border-t border-gray-100 pt-5"
            >
              <span class="text-sm text-gray-500"> Obra comercial </span>

              <span
                class="text-sm font-semibold text-gray-900 transition group-hover:translate-x-1"
              >
                Ver proyecto →
              </span>
            </div>
          </div>
        </article>
      </div>

      <!-- CTA -->
      <div class="mt-16 text-center">
        <p class="text-gray-600">¿Tenés un proyecto en mente?</p>

        <a
          href="#contacto"
          class="mt-4 inline-flex items-center justify-center rounded-lg bg-gray-900 px-7 py-3.5 text-sm font-semibold text-white transition hover:bg-gray-700"
        >
          Hablemos de tu proyecto
        </a>
      </div>
    </div>
  </section>
</template>
