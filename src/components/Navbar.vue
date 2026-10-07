<template>
  <header class="sticky top-0 z-50 bg-white shadow-sm">
    <nav
      class="mx-auto flex max-w-7xl items-center justify-between px-6 py-4 lg:px-8"
    >
      <!-- Logo -->
      <a href="#inicio" class="flex items-center">
        <img
          src="/images/logo-concreta-navbar.jpeg"
          alt="CONCRETA - Soluciones Integrales"
          class="h-16 w-auto object-contain"
        />
      </a>

      <!-- Menú desktop -->
      <div class="hidden items-center gap-8 md:flex">
        <a
          href="#inicio"
          class="text-sm font-medium text-gray-700 transition hover:text-gray-900"
        >
          Inicio
        </a>

        <a
          href="#nosotros"
          class="text-sm font-medium text-gray-700 transition hover:text-gray-900"
        >
          Nosotros
        </a>

        <a
          href="#servicios"
          class="text-sm font-medium text-gray-700 transition hover:text-gray-900"
        >
          Servicios
        </a>

        <a
          href="#obras"
          class="text-sm font-medium text-gray-700 transition hover:text-gray-900"
        >
          Obras
        </a>

        <a
          href="#contacto"
          class="rounded-lg bg-gray-900 px-5 py-2.5 text-sm font-medium text-white transition hover:bg-gray-700"
        >
          Contacto
        </a>
      </div>

      <!-- Botón menú móvil -->
      <button
        type="button"
        class="rounded-lg p-2 text-gray-700 transition hover:bg-gray-100 md:hidden"
        aria-label="Abrir menú"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-6 w-6"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          stroke-width="2"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M4 6h16M4 12h16M4 18h16"
          />
        </svg>
      </button>
    </nav>
  </header>
</template>
