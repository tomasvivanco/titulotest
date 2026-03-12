# Seminario de Título 2026 (Build)

Esta rama publica la versión construida de la aplicación **Seminario de Título**. El archivo `index.html` y la carpeta `assets/` provienen de ejecutar `npm install && npm run build` dentro de `/repo` (el código fuente original en React + Vite). El bundle resultante ya no depende de `type="text/babel"` y cumple las políticas CSP de GitHub Pages.

Para regenerar el build (desde el repositorio fuente `/repo`):
1. `cd /Users/tomas/titulotest/repo`
2. `npm install`
3. `npm run build`
4. Copia el contenido de `dist/` a este directorio (`cp -r dist/* /Users/tomas/titulotest/repo2/`).

GitHub Pages puede servir directamente esta carpeta (`main`/root) porque `dist/index.html` referencia los assets con `base: '/titulotest/'`.
