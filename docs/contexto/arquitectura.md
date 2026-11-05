# Arquitectura del Proyecto: El Campeón del Siglo

## 1. Stack Tecnológico
*   **Estructura:** HTML5 semántico en un único archivo `index.html` (SPA sin recarga).
*   **Estilos:** TailwindCSS vía CDN, con `darkMode: 'class'` y colores extendidos (`river`).
*   **Lógica:** JavaScript vanilla (sin frameworks), embebido al final de `index.html`.
*   **Tipografías:** Google Fonts `Oswald` (títulos) y `Roboto` (cuerpo).
*   **Persistencia:** `localStorage` solo para la preferencia de tema.

## 2. Mapa de Módulos (Vistas de la SPA)
1.  **Header/Navbar:** Fijo arriba, logo, menú de escritorio, botón de tema y menú hamburguesa en móvil.
2.  **Vista Inicio (`#view-inicio`):** Hero + 3 tarjetas informativas (Noticias, Fixture, Tienda).
3.  **Vista Catálogo (`#view-catalogo`):** Buscador + 6 tarjetas de producto con modal "Ver más". Implementa los 4 estados UI.
4.  **Vista Contacto (`#view-contacto`):** Formulario validado con aviso verde de éxito.
5.  **Modal de Producto (`#modal`):** Cierra con botón, ✕, clic en el fondo o tecla Escape.
6.  **Footer:** Información del medio.

## 3. Tecnologías Prohibidas
*   React, Vue, Angular u otro framework SPA.
*   Bundlers (Vite, Webpack) y pasos de build.
*   Backend propio (FastAPI, Node, etc.) y bases de datos.
*   Librerías CSS adicionales (Bootstrap) o CSS-in-JS.
