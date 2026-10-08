# ⚡ Sports Shop - Tienda Deportiva
Proyecto web desarrollado para la pre-entrega del curso de **Desarrollo Front-End**. Se trata de un sitio web para una tienda de indumentaria y calzado deportivo, enfocado en buenas prácticas de maquetado semántico con **HTML5** y estilizado responsivo con **CSS3**.
---
## 🚀 Tecnologías Implementadas
- **HTML5:** Estructuración semántica del contenido (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- **CSS3:** 
  - **Reset y Box Model:** Normalización de márgenes y uso de `box-sizing: border-box`.
  - **Tipografía:** Integración de fuentes externas mediante Google Fonts (*Poppins*).
  - **Flexbox:** Distribución de la barra de navegación, alineación de elementos y control del layout para fijar el footer (`flex: 1`).
  - **CSS Grid:** Organización del catálogo en dos columnas, con la sección de ofertas expandida (`grid-column: 1 / -1`) y productos en tres columnas.
  - **Selectores Avanzados y Pseudo-clases:** Uso de selectores directos (`>`), `:hover`, `:focus`, `:last-child` y `:nth-of-type()` para estilizar precios y estados interactivos.
  - **Diseño Responsivo (Media Queries):** Adaptación fluida para dispositivos móviles y tablets mediante `@media (max-width: 768px)`.
---
## 📂 Estructura del Proyecto
```text
Entrega/
├── index.html              # Página principal con catálogo y secciones
├── pages/
│   └── contactos.html      # Página con formulario de contacto funcional (Formspree)
├── styles/
│   └── styles.css          # Hoja de estilos general y responsive
└── img/                    # Imágenes de fondo y productos
