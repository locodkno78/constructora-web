<template>
  <section id="nosotros" class="bg-white py-24 sm:py-32">
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <!-- Contenido principal -->
      <div class="grid items-center gap-12 lg:grid-cols-2 lg:gap-20">
        <!-- Imagen -->
        <div class="relative">
          <div class="overflow-hidden rounded-2xl">
            <img
              src="https://images.unsplash.com/photo-1504307651254-35680f356dfd?auto=format&fit=crop&w=1200&q=85"
              alt="Equipo trabajando en una obra"
              class="h-[500px] w-full object-cover"
            />
          </div>

          <!-- Tarjeta superpuesta -->
          <div
            class="absolute -bottom-8 -right-4 hidden rounded-xl bg-gray-900 px-8 py-6 text-white shadow-xl sm:block lg:-right-8"
          >
            <p class="text-3xl font-bold">+15</p>

            <p class="mt-1 text-sm text-gray-300">años de experiencia</p>
          </div>
        </div>

        <!-- Texto -->
        <div>
          <p
            class="text-sm font-semibold uppercase tracking-[0.3em] text-gray-500"
          >
            Sobre nosotros
          </p>

          <h2
            class="mt-4 text-4xl font-bold tracking-tight text-gray-900 sm:text-5xl"
          >
            Construimos mucho más que espacios.
          </h2>

          <p class="mt-6 text-lg leading-8 text-gray-600">
            Somos una empresa dedicada al desarrollo y ejecución de proyectos de
            construcción, comprometida con ofrecer soluciones de calidad y
            resultados que perduren en el tiempo.
          </p>

          <p class="mt-5 leading-7 text-gray-600">
            Trabajamos junto a nuestros clientes desde la planificación inicial
            hasta la finalización de cada proyecto, cuidando cada detalle y
            buscando siempre superar las expectativas.
          </p>

          <!-- Valores -->
          <div class="mt-8 space-y-5">
            <div class="flex gap-4">
              <div
                class="flex h-7 w-7 shrink-0 items-center justify-center rounded-full bg-gray-900 text-sm text-white"
              >
                ✓
              </div>

              <div>
                <h3 class="font-semibold text-gray-900">Experiencia</h3>

                <p class="mt-1 text-sm leading-6 text-gray-600">
                  Conocimiento y experiencia aplicados en cada proyecto.
                </p>
              </div>
            </div>

            <div class="flex gap-4">
              <div
                class="flex h-7 w-7 shrink-0 items-center justify-center rounded-full bg-gray-900 text-sm text-white"
              >
                ✓
              </div>

              <div>
                <h3 class="font-semibold text-gray-900">Calidad</h3>

                <p class="mt-1 text-sm leading-6 text-gray-600">
                  Materiales y procesos seleccionados para lograr resultados
                  duraderos.
                </p>
              </div>
            </div>

            <div class="flex gap-4">
              <div
                class="flex h-7 w-7 shrink-0 items-center justify-center rounded-full bg-gray-900 text-sm text-white"
              >
                ✓
              </div>

              <div>
                <h3 class="font-semibold text-gray-900">Compromiso</h3>

                <p class="mt-1 text-sm leading-6 text-gray-600">
                  Acompañamos al cliente durante todo el proceso.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Estadísticas -->
      <div
        class="mt-24 grid grid-cols-1 divide-y border-y border-gray-200 sm:grid-cols-3 sm:divide-x sm:divide-y-0"
      >
        <div class="px-6 py-8 text-center">
          <p class="text-4xl font-bold text-gray-900">+15</p>

          <p class="mt-2 text-sm text-gray-500">Años de experiencia</p>
        </div>

        <div class="px-6 py-8 text-center">
          <p class="text-4xl font-bold text-gray-900">+80</p>

          <p class="mt-2 text-sm text-gray-500">Obras realizadas</p>
        </div>

        <div class="px-6 py-8 text-center">
          <p class="text-4xl font-bold text-gray-900">+10</p>

          <p class="mt-2 text-sm text-gray-500">Proyectos en curso</p>
        </div>
      </div>
    </div>
  </section>
</template>
