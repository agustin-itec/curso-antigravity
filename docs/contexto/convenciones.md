# Convenciones de Desarrollo

## 1. Diseño y Paleta de Colores
*   **Fondo Base:** Blanco puro (`bg-white`).
*   **Color Primario:** Rojo estilo River Plate (ej. `bg-red-600` o `#D50000`). Se aplica en el Navbar y secciones destacadas.
*   **Textos:** Negro (`text-black`) o Gris Oscuro (`text-gray-900`) para fondos claros. Texto Blanco (`text-white`) sobre fondos rojos.
*   **Modo Oscuro:** Fondo `dark:bg-gray-950`, texto `dark:text-gray-100`. Toda superficie roja lleva `.force-text-white`.

## 2. Tipografía (Google Fonts)
*   **Títulos:** `Oswald` o `Roboto Condensed` (Transmite espíritu deportivo e informativo).
*   **Cuerpo / Párrafos:** `Roboto` o `Inter` (Prioriza la legibilidad).

## 3. Diseño Responsivo (Mobile-First)
*   **Escritorio (Desktop):** Las grillas de productos y noticias se muestran en 3 columnas (`grid-cols-3`). El menú de navegación es horizontal.
*   **Móviles (Mobile):** Todo pasa a 1 columna vertical (`grid-cols-1`). El menú colapsa en un botón hamburguesa.

## 4. Interactividad Visual (Hover)
*   **Botones:** Cambio de brillo al pasar el mouse (`hover:brightness-110` o `hover:bg-red-700`).
*   **Tarjetas (Cards):** Elevación (`hover:-translate-y-1`), sombra suave (`hover:shadow-xl`), y ligero zoom en la imagen contenida (`hover:scale-105` con `transition-transform`).

## 5. Etiquetas Semánticas
*   Usar `<header>`, `<main>`, `<section>`, `<article>`, `<nav>` y `<footer>` según corresponda.
*   Elementos de acción (clic) deben ser **siempre** etiquetas `<button>`.
