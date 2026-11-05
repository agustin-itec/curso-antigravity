# Errores Conocidos y Gotchas de Maquetado

Esta lista funciona como protección contra los errores más comunes de desarrollo web. **Se deben revisar en cada fase del maquetado.**

1.  **Scroll Horizontal Roto en Celulares:**
    *   *Problema:* Contenido más ancho que la pantalla genera un desplazamiento lateral no deseado.
    *   *Prevención:* Aplicar siempre `overflow-x-hidden` en el `<body>` o `<main>`.
2.  **Imágenes Inaccesibles:**
    *   *Problema:* Los lectores de pantalla no pueden leer fotos.
    *   *Prevención:* Es obligatorio agregar el atributo `alt="Descripción"` en todas las etiquetas `<img>`.
3.  **Botones "Falsos":**
    *   *Problema:* Usar `<div class="boton">` rompe la navegación por teclado y la accesibilidad.
    *   *Prevención:* Elementos que ejecutan acciones de JavaScript deben ser obligatoriamente etiquetas `<button>`.
4.  **Contraste Ilegible:**
    *   *Problema:* Texto oscuro sobre fondo oscuro, o texto rojo sobre fondo rojo.
    *   *Prevención:* Asegurar que sobre los fondos principales rojos (`bg-red-600`) el texto sea siempre blanco (`text-white`) y en los fondos blancos sea oscuro (`text-gray-900`).
