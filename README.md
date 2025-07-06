# Las Arepas del Parcero

¡Bienvenido al sitio web de "Las Arepas del Parcero"! Este proyecto es una página web desarrollada con Astro, diseñada para mostrar nuestros productos y permitir a los clientes contactarnos fácilmente a través de WhatsApp.

## ✨ Características

-   **Listado de Productos:** Muestra una variedad de arepas y otros productos con sus imágenes y precios.
-   **Contacto Directo por WhatsApp:** Incluye un botón de "Llamada a la Acción" (CTA) que permite a los usuarios enviar un mensaje predefinido directamente a nuestro WhatsApp.
-   **Diseño Responsivo:** Adaptado para verse bien en dispositivos móviles, tabletas y escritorios, utilizando Tailwind CSS para un diseño flexible y moderno.
-   **Componentes Reutilizables:** Estructura modular con componentes Astro para facilitar el mantenimiento y la escalabilidad.

## 🚀 Estructura del Proyecto

Dentro de este proyecto de Astro, encontrarás la siguiente estructura de carpetas y archivos clave:

```text
/
├── public/
│   ├── favicon.svg
│   ├── imagenes/             # Imágenes generales del sitio (logo, hero, contacto, ubicacion)
│   └── products/             # Imágenes de los productos
├── src/
│   ├── assets/
│   ├── components/           # Componentes reutilizables (Product, Footer, iconos)
│   │   ├── Footer.astro
│   │   ├── Product.astro
│   │   └── icons/            # Componentes de iconos SVG
│   ├── layouts/
│   │   └── Layout.astro      # Layout principal de la página
│   ├── pages/
│   │   └── index.astro       # Página principal del sitio
│   └── styles/
│       ├── colors.css
│       ├── global.css
│       └── tailwind.css
├── astro.config.mjs
├── package.json
├── tailwind.config.js
├── tsconfig.json
└── README.md
```

Para aprender más sobre la estructura de carpetas de un proyecto Astro, consulta [nuestra guía sobre la estructura del proyecto](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto, desde una terminal:

| Comando                   | Acción                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Instala las dependencias                         |
| `npm run dev`             | Inicia el servidor de desarrollo local en `localhost:4321` |
| `npm run build`           | Compila tu sitio para producción en `./dist/`    |
| `npm run preview`         | Previsualiza tu compilación localmente, antes de desplegar |
| `npm run astro ...`       | Ejecuta comandos CLI como `astro add`, `astro check` |
| `npm run astro -- --help` | Obtén ayuda usando la CLI de Astro               |

## 👀 ¿Quieres aprender más?

No dudes en consultar [nuestra documentación](https://docs.astro.build) o unirte a nuestro [servidor de Discord](https://astro.build/chat).