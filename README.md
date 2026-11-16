# SGF – Sitio de presentación

Sitio web estático que presenta el proyecto **SGF – Sistema de Gestión de Farmacia** (proyecto formativo SENA, programa ADSO). Solo HTML, CSS y un JS mínimo para el menú móvil; sin dependencias ni rastreo.

## Ver en local

Abre `index.html` en el navegador.

## Publicar en GitHub Pages

1. Crea un repositorio público llamado `sgf-presentacion` en GitHub.
2. Sube el contenido:
   ```bash
   git remote add origin https://github.com/USUARIO/sgf-presentacion.git
   git push -u origin main
   ```
3. En el repositorio: **Settings → Pages → Build and deployment**.
   - Source: **Deploy from a branch**
   - Branch: **main** / **(root)** → **Save**
4. En unos minutos el sitio estará en `https://USUARIO.github.io/sgf-presentacion/`.

## Reemplazar las capturas

Sustituye los archivos de `img/capturas/` (`captura-1.png` a `captura-4.png`) por capturas reales con datos de prueba, manteniendo los mismos nombres. Si cambias su contenido, actualiza el texto `alt` y el pie de foto en `capturas.html`.
