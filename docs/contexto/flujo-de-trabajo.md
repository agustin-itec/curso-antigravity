# Flujo de Trabajo y Control de Calidad

## 1. Fases de Desarrollo (Metodología SDD)
El desarrollo de toda nueva funcionalidad o vista debe seguir estrictamente este orden:
1.  **Estructura Semántica (HTML5):** Definir el esqueleto y etiquetas adecuadas (`header`, `main`, `section`) sin preocuparse por el diseño inicial.
2.  **Maquetación y Diseño (TailwindCSS):** Aplicar clases utilitarias para lograr colores, tipografías, grillas de 3 columnas en PC y 1 en móviles.
3.  **Interactividad (JavaScript):** Agregar la lógica final para abrir/cerrar menú móvil y modales.

## 2. Definition of Done (DoD) - Checklist de Verificación
Antes de considerar cualquier tarea como finalizada, se debe validar:
*   [ ] **Validación Visual (Desktop):** La página se ve bien en pantalla ancha y las tarjetas tienen 3 columnas.
*   [ ] **Validación Visual (Mobile):** Probar con *Responsive Mode* (F12) o achicando la ventana: No hay scroll horizontal y todo pasa a 1 columna.
*   [ ] **Interactividad:** El menú hamburguesa abre y cierra. Los botones "Ver más" y los modales responden correctamente.
*   [ ] **Consola Limpia:** No hay errores rojos ni warnings en la consola de JavaScript del navegador.
*   [ ] **Feedback UI:** Todo botón y enlace tiene efectos `hover` visibles.
