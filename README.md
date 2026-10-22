# EcoMarket

[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/andrewk-g/proyecto_web)

## Documentación en DeepWiki
Puedes consultar la documentación interactiva y arquitectura detallada del proyecto en DeepWiki:
- **Enlace DeepWiki:** [https://deepwiki.com/andrewk-g/proyecto_web](https://deepwiki.com/andrewk-g/proyecto_web)
- **Repositorio en GitHub:** [https://github.com/andrewk-g/proyecto_web](https://github.com/andrewk-g/proyecto_web)

---

## Nombre del proyecto
**EcoMarket** — Tienda virtual ecológica, reutilizable y sostenible.

## Descripción
EcoMarket es una tienda web estática desarrollada exclusivamente con **HTML5 semántico** y **CSS3 puro**. Su objetivo es presentar un catálogo de productos ecológicos con una identidad visual inspirada en la naturaleza, el consumo consciente y el diseño editorial moderno.

## Objetivo del proyecto
Crear una experiencia visual atractiva, moderna y responsiva para una tienda virtual ecológica, cumpliendo estrictamente con el uso exclusivo de **HTML5 y CSS3** (sin JavaScript, sin frameworks ni librerías externas).

## Características principales
- **HTML5 semántico** y arquitectura modular por archivos.
- **CSS3 puro** con **Variables CSS**, **Flexbox**, **CSS Grid**, **Media Queries**, pseudoclases (`:hover`, `:checked`, `:focus-within`, `:valid`, `:invalid`) y animaciones.
- **Navbar interactivo en CSS** con efecto de cápsula elástica, indicador luminoso inferior, iconos SVG animados y menú hamburguesa móvil que se transforma en `X`.
- **Mapa interactivo simulado (100% HTML y CSS)** con imagen satelital de Bucaramanga (`img/mapa.png`), marcador con ondas de radar, radio de cobertura animado, tarjeta flotante al pasar el cursor y control de zoom (`+` / `−`) mediante `checkbox` CSS.
- **Cuatro vistas completas**: Inicio, Productos (catálogo), Sobre nosotros y Contacto.
- **Catálogo con 20 productos** distribuidos en cuatro categorías: Hogar, Moda, Cuidado personal y Alimentos.
- **Favoritos interactivos** con `checkbox` oculto + `label` y animación de latido.
- **Productos agotados** con etiqueta visual y estado deshabilitado.
- **Formulario de contacto** con validación HTML nativa y estados visuales dinámicos.
- **Carrusel horizontal** con CSS `scroll-snap` para testimonios.
- **Accesibilidad y rendimiento**: soporte para `prefers-reduced-motion`, navegación por teclado (`:focus-visible`) y diseño *Mobile First*.

## Tecnologías utilizadas
- **HTML5**
- **CSS3** (Custom Properties, CSS Grid, Flexbox, Media Queries, Keyframes, Scroll-Driven Animations)

## Estructura de carpetas
```text
proyecto_web/
│
├── index.html                  # Vista principal (Inicio + Mapa interactivo)
│
├── css/
│   ├── main.css                # Reset, variables globales y tipografía
│   ├── layout.css              # Cabecera, navbar animado, grids y footer
│   ├── components.css          # Botones, tarjetas 3D, filtros, formularios y mapa CSS
│   └── animations.css          # Animaciones vinculadas al scroll y keyframes
│
├── img/
│   ├── logo.png                # Logotipo de EcoMarket
│   ├── mapa.png                # Imagen satelital del mapa de Bucaramanga
│   ├── products/               # Fotografías e ilustraciones de productos
│   ├── icons/                  # Iconos SVG ecológicos
│   └── hero/                   # Imágenes principales de secciones
│
├── views/
│   ├── productos.html          # Catálogo completo con filtros visuales
│   ├── sobre-nosotros.html     # Historia, misión, visión y carrusel de testimonios
│   └── contacto.html           # Formulario validado y mapa interactivo CSS
│
└── README.md                   # Documentación del proyecto
```

## Descripción de las cuatro vistas
| Vista | Archivo | Descripción |
|---|---|---|
| **Inicio** | `index.html` | Hero con profundidad 3D, beneficios, productos destacados, bloque de sostenibilidad, sección de ubicación con mapa interactivo y pie de página. |
| **Productos** | `views/productos.html` | Catálogo con 20 productos, barra de búsqueda visual, filtros laterales, favoritos con checkbox CSS y paginación visual. |
| **Sobre nosotros** | `views/sobre-nosotros.html` | Propósito, misión y visión, principios ecológicos y carrusel horizontal de testimonios con CSS puro. |
| **Contacto** | `views/contacto.html` | Formulario con validación nativa HTML/CSS, datos de contacto y mapa interactivo simulado de Bucaramanga con zoom y marcador animado. |

## Instrucciones para ejecutar el proyecto localmente
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/andrewk-g/proyecto_web.git
   ```
2. Abrir la carpeta del proyecto en **Visual Studio Code**.
3. Ejecutar `index.html` con la extensión **Live Server** o abrirlo directamente en el navegador.

## Nota académica
Los productos, precios, testimonios, datos de contacto y ubicación son de carácter demostrativo y académico, implementados únicamente con HTML y CSS.
