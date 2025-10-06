# Reposteria Rossy — Astro + Tailwind scaffold

Contenido:
- Páginas: `index.astro`, `catalogo.astro`, `carrito.astro`, `nosotros.astro`
- Estilos por página en `src/styles/`
- Un componente cliente React `CartClient.jsx` que maneja el carrito en localStorage (persistencia local).
- Tailwind integrado (usa `src/styles/global.css`).

Cómo usar:
1. Descomprime el zip y entra en la carpeta.
2. Ejecuta `npm install`
3. Ejecuta `npm run dev` para correr en modo desarrollo.

Notas:
- Mejoré visualmente con Tailwind (bordes, sombras, tipografía).
- El carrito funciona en el frontend usando `localStorage`. Fácil de conectar a un backend en el futuro.
