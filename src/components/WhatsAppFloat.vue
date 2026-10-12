
<template>
  <a
    :href="whatsappLink"
    target="_blank"
    rel="noopener noreferrer"
    aria-label="Contactar por WhatsApp"
    title="¡Escribinos por WhatsApp!"
    class="fixed bottom-6 right-5 z-[100] flex h-14 w-14 items-center justify-center rounded-full bg-[#25D366] text-white shadow-lg transition duration-300 hover:scale-110 hover:bg-[#20BA5A] sm:bottom-8 sm:right-8 sm:h-16 sm:w-16"
  >
    <svg
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 24 24"
      fill="currentColor"
      class="h-8 w-8 sm:h-9 sm:w-9"
      aria-hidden="true"
    >
      <path
        d="M20.52 3.48A11.8 11.8 0 0 0 12.08 0C5.53 0 .19 5.34.19 11.9c0 2.1.55 4.16 1.6 5.98L.1 24l6.28-1.65a11.9 11.9 0 0 0 5.69 1.45h.01c6.55 0 11.9-5.34 11.9-11.9 0-3.18-1.24-6.17-3.46-8.42ZM12.08 21.8a9.9 9.9 0 0 1-5.04-1.38l-.36-.21-3.73.98.99-3.64-.24-.38a9.86 9.86 0 0 1-1.52-5.27c0-5.47 4.45-9.92 9.92-9.92 2.65 0 5.14 1.03 7.02 2.91a9.87 9.87 0 0 1 2.9 7.03c0 5.47-4.45 9.92-9.92 9.92Zm5.44-7.43c-.3-.15-1.77-.87-2.04-.97-.27-.1-.47-.15-.67.15-.2.3-.77.97-.95 1.17-.17.2-.35.22-.65.07-.3-.15-1.26-.46-2.4-1.47-.89-.8-1.49-1.78-1.66-2.08-.17-.3-.02-.46.13-.61.14-.14.3-.35.45-.52.15-.17.2-.3.3-.5.1-.2.05-.37-.03-.52-.07-.15-.67-1.62-.92-2.22-.24-.58-.49-.5-.67-.51h-.57c-.2 0-.52.07-.79.37-.27.3-1.04 1.02-1.04 2.49s1.07 2.89 1.22 3.09c.15.2 2.1 3.21 5.08 4.5.71.31 1.26.49 1.69.63.71.22 1.35.19 1.86.12.57-.08 1.77-.72 2.02-1.42.25-.7.25-1.3.17-1.42-.07-.12-.27-.2-.57-.35Z"
      />
    </svg>
  </a>
</template>

<script setup>
const whatsappNumber = '5493813027176'

const whatsappMessage = encodeURIComponent(
  'Hola, quiero realizar una consulta sobre CONCRETA.'
)

const whatsappLink =
  `https://wa.me/${whatsappNumber}?text=${whatsappMessage}`
</script>
