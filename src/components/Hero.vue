<template>
  <section
    id="inicio"
    class="relative flex min-h-[calc(100vh-73px)] items-center overflow-hidden"
  >

```
<!-- Imagen de fondo -->
<div class="absolute inset-0">
  <img
    src="https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=2000&q=85"
    alt="Proyecto de construcción"
    class="h-full w-full object-cover"
  />
</div>

<!-- Overlay -->
<div class="absolute inset-0 bg-black/55"></div>

<!-- Contenido -->
<div class="relative z-10 mx-auto w-full max-w-7xl px-6 py-20 lg:px-8">

  <div class="max-w-3xl">

    <p class="mb-5 text-sm font-semibold uppercase tracking-[0.3em] text-white/80">
      Construcción · Diseño · Calidad
    </p>

    <h1 class="text-5xl font-bold leading-tight text-white sm:text-6xl lg:text-7xl">
      Construimos
      <span class="block">
        el futuro.
      </span>
    </h1>

    <p class="mt-6 max-w-2xl text-lg leading-relaxed text-white/85 sm:text-xl">
      Desarrollamos proyectos de construcción con compromiso,
      experiencia y atención en cada detalle.
    </p>

    <!-- Botones -->
    <div class="mt-10 flex flex-col gap-4 sm:flex-row">

      <a
        href="#obras"
        class="rounded-lg bg-white px-7 py-3.5 text-center text-sm font-semibold text-gray-900 transition hover:bg-gray-200"
      >
        Ver nuestras obras
      </a>

      <a
        href="#contacto"
        class="rounded-lg border border-white/70 px-7 py-3.5 text-center text-sm font-semibold text-white transition hover:bg-white hover:text-gray-900"
      >
        Solicitar consulta
      </a>

    </div>

  </div>

</div>

<!-- Indicador de scroll -->
<a
  href="#nosotros"
  class="absolute bottom-8 left-1/2 hidden -translate-x-1/2 flex-col items-center gap-2 text-white/70 transition hover:text-white md:flex"
>
  <span class="text-xs uppercase tracking-widest">
    Descubrí más
  </span>

  <svg
    xmlns="http://www.w3.org/2000/svg"
    class="h-5 w-5 animate-bounce"
    fill="none"
    viewBox="0 0 24 24"
    stroke="currentColor"
    stroke-width="2"
  >
    <path
      stroke-linecap="round"
      stroke-linejoin="round"
      d="M19 9l-7 7-7-7"
    />
  </svg>
</a>
```

  </section>
</template>
