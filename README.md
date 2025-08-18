# Ainsophic — GitHub Pages static site

Esta carpeta contiene una versión estática del hub *Ainsophic* lista para desplegar en **GitHub Pages**.

## Estructura
- `index.html` — Página principal del hub.
- `projects/` — Fichas individuales por proyecto (HTML).
- `.nojekyll` — Archivo vacío para desactivar procesamiento Jekyll (incluido).

## Cómo desplegar (rápido)
1. Crear un repositorio en GitHub, por ejemplo `ainsophic.github.io` o una organización `ainsophic` con repositorio `website`.
2. Copiar el contenido de esta carpeta al repositorio (root).
3. Hacer `git add . && git commit -m "Site inicial" && git push origin main`.
4. En GitHub: Settings → Pages → Source: `main` branch / root (o `gh-pages` branch si preferís).
5. Esperar unos segundos. El sitio estará disponible en `https://<tu_usuario>.github.io/<repo>` o `https://ainsophic.github.io` si usas ese repo.

## Notas
- Los enlaces a los repositorios apuntan a `https://github.com/ainsophic/<repo>`; actualizalos si tu organización o nombres difieren.
- Si querés agregar más proyectos, crear archivos `projects/<Proyecto>.html` y añadir enlaces en `projects/index.html`.
- Considerar agregar un `CNAME` si vas a usar dominio custom, y un archivo `LICENSE` para repositorios.
