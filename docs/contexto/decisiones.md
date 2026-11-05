# Registro de Decisiones Arquitectónicas (ADRs)

*Toda decisión técnica registrada aquí es de cumplimiento obligatorio. Se requiere autorización previa y validación del impacto antes de alterar estas reglas.*

## [ADR-001] Stack de Frontend: React + Vite + Tailwind — ❌ REEMPLAZADA por ADR-003
*   **Fecha:** 2026-09-14
*   **Decisión original:** Adoptar React 18+ con TypeScript, Vite y TailwindCSS.

## [ADR-002] Stack de Backend: Python + FastAPI + SQLModel — ❌ REEMPLAZADA por ADR-003
*   **Fecha:** 2026-09-14
*   **Decisión original:** Backend con FastAPI y SQLModel bajo patrón Repository.

## [ADR-003] Volver a una SPA en un único `index.html`
*   **Fecha:** 2026-11-05 10:30
*   **Autorización:** Confirmada explícitamente por el cliente (borrado de `frontend/` y `backend/`).
*   **Decisión:** HTML5 + TailwindCSS (CDN) + JavaScript vanilla en un solo archivo, sin backend.
*   **Justificación:** El Requisito 1 del Desafío Integrador (Clase 07) exige una página única en `index.html`. El stack React/FastAPI excedía el alcance y no cumplía la consigna.

## [ADR-004] Modo Claro/Oscuro con clase `.dark` y `.force-text-white`
*   **Fecha:** 2026-11-05 10:30
*   **Decisión:** Tailwind `darkMode: 'class'`, preferencia guardada en `localStorage`; las superficies rojas usan `.force-text-white`.
*   **Justificación:** Requisito 3 de la consigna y prevención del gotcha de contraste.
