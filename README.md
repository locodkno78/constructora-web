# Constructora Web

Sitio web institucional desarrollado para una empresa constructora, con un diseño moderno, profesional y responsive.

El proyecto presenta los servicios de la empresa, sus membresías de mantenimiento, obras realizadas y diferentes medios de contacto.

## 🚧 Estado del proyecto

**En desarrollo**

La primera versión visual del sitio se encuentra construida. Quedan pendientes algunas funcionalidades y la incorporación de los datos reales de la empresa.

---

## 🛠️ Tecnologías utilizadas

* **Vue 3**
* **Vite**
* **JavaScript**
* **Tailwind CSS**
* **HTML5**
* **CSS3**
* **Git**
* **GitHub**

---

## 📁 Estructura del proyecto

```text
constructora-web/
│
├── public/
│
├── src/
│   ├── components/
│   │   ├── Navbar.vue
│   │   ├── Hero.vue
│   │   ├── About.vue
│   │   ├── Services.vue
│   │   ├── Works.vue
│   │   ├── Contact.vue
│   │   └── Footer.vue
│   │
│   ├── App.vue
│   ├── main.js
│   └── style.css
│
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```

---

## 🏗️ Secciones del sitio

### Navbar

Barra de navegación principal con acceso a:

* Inicio
* Nosotros
* Servicios
* Obras
* Contacto

Incluye un logo temporal que será reemplazado por el logo definitivo de la empresa.

### Hero

Sección principal de presentación con:

* Imagen de fondo
* Mensaje principal
* Descripción de la empresa
* Acceso a las obras
* Acceso al contacto

### Nosotros

Presentación institucional de la empresa y sus principales valores:

* Experiencia
* Calidad
* Compromiso

También incluye estadísticas que actualmente funcionan como datos de ejemplo y deberán reemplazarse por información real.

### Membresías CONCRETA

Sección destinada a los planes de mantenimiento de la empresa:

#### Básico

* Albañilería
* Pintura
* Electricidad
* Gasista
* Abono mensual

#### Premium

* Albañilería
* Pintura
* Electricidad
* Gasista
* Limpieza de canaletas
* Poda / Mantenimiento de césped
* Atención 24 hs.
* Abono mensual

#### Comercial

* Albañilería
* Pintura
* Electricidad
* Gasista
* Limpieza de canaletas
* Poda / Mantenimiento de césped
* Atención 24 hs.
* Mantenimiento preventivo
* Abono mensual

Los precios se encuentran actualmente como valores temporales y serán reemplazados por los montos definitivos.

Los botones de consulta utilizan WhatsApp.

### Obras

Galería inicial de proyectos con:

* Imagen
* Categoría
* Nombre del proyecto
* Descripción
* Acceso para futuras ampliaciones

Las obras actuales utilizan contenido e imágenes provisionales.

### Contacto

Sección de contacto con:

* WhatsApp
* Teléfono
* Email
* Ubicación
* Formulario de consulta

El formulario se encuentra actualmente diseñado a nivel visual. La conexión con un servicio de envío de emails será incorporada posteriormente.

### Footer

Pie de página con:

* Identidad de la empresa
* Navegación
* Datos de contacto
* Redes sociales
* WhatsApp
* Copyright

---

## 🚀 Instalación

Clonar el repositorio:

```bash
git clone https://github.com/locodkno78/constructora-web.git
```

Ingresar al proyecto:

```bash
cd constructora-web
```

Instalar dependencias:

```bash
npm install
```

---

## 💻 Desarrollo

Para iniciar el servidor de desarrollo:

```bash
npm run dev
```

Luego abrir la dirección indicada por Vite, normalmente:

```text
http://localhost:5173
```

---

## 📦 Build de producción

Para generar la versión de producción:

```bash
npm run build
```

Los archivos generados estarán disponibles en:

```text
dist/
```

Para comprobar localmente la versión de producción:

```bash
npm run preview
```

---

## 📱 Diseño responsive

El sitio está desarrollado con un enfoque responsive para adaptarse a:

* 📱 Teléfonos
* 📲 Tablets
* 💻 Notebooks
* 🖥️ Monitores de escritorio

Tailwind CSS permite controlar los distintos tamaños de pantalla mediante sus clases responsive.

---

## 🔗 Integraciones previstas

Durante las próximas etapas se prevé incorporar:

* [ ] Logo definitivo
* [ ] Datos reales de la empresa
* [ ] Precios definitivos de las membresías
* [ ] Obras reales y fotografías propias
* [ ] Menú móvil funcional
* [ ] Formulario de contacto funcional
* [ ] Integración con EmailJS o Formspree
* [ ] Enlaces reales de redes sociales
* [ ] Número real de WhatsApp
* [ ] Animaciones y mejoras visuales
* [ ] Detalle individual de cada obra
* [ ] Optimización SEO
* [ ] Deploy definitivo

---

## 🔐 Seguridad

El proyecto es principalmente institucional y no requiere actualmente una base de datos ni autenticación de usuarios.

Las futuras integraciones deberán evitar exponer claves privadas o información sensible en el código del frontend.

---

## 🌐 Repositorio

Repositorio oficial:

**GitHub:**
https://github.com/locodkno78/constructora-web

---

## 👨‍💻 Autor

**Di Colantonio Santiago**

Desarrollo web con Vue.js, JavaScript, HTML, CSS y tecnologías modernas de frontend.

---

## 📄 Licencia

Proyecto desarrollado para uso institucional de la empresa constructora.

Todos los derechos reservados.


