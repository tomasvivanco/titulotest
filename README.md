# Seminario de Título 2026 (Static)

Este repositorio contiene la versión autopublicable de la aplicación **Seminario de Título** construida como un único `index.html` que funciona directamente en el navegador sin pasos de compilación.

## Cómo usarlo
1. Abre `index.html` en cualquier navegador moderno.
2. La app usa React, ReactDOM y Babel desde CDN para cargar el código embebido.
3. Todos los datos se almacenan en IndexedDB/localStorage; el usuario se autentica contra el conjunto demo (`demo.profesor@.../Demo2026` y `demo.estudiante@.../Demo2026`).

## Publicación en GitHub Pages
1. En el repositorio de GitHub, ve a **Settings > Pages**.
2. Selecciona la rama `main` y la carpeta `/ (root)` como origen, guarda.
3. GitHub Pages publicará automáticamente `index.html` desde esta rama.
4. Comparte la URL proporcionada en la misma página (algo como `https://tu-usuario.github.io/titulotest`).

No hace falta construir nada ni instalar dependencias; cualquier cambio en `index.html` se refleja al hacer push a `main`.
