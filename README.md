# Electria

Experiencia interactiva sobre música e inteligencia artificial (HTML + CSS + JS, sitio estático).

## Publicar en GitHub Pages

1. Subí **todo el contenido de esta carpeta** a la raíz de un repositorio (`index.html` debe quedar en la raíz).
2. En GitHub: **Settings → Pages → Build and deployment**.
3. En *Source* elegí **Deploy from a branch**, rama `main`, carpeta `/ (root)`, y guardá.
4. En 1–2 minutos queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

No requiere build ni dependencias. Las rutas son relativas, por lo que funciona en subcarpetas de GitHub Pages.

## Probar en local

```bash
python3 -m http.server 8000
# abrir http://localhost:8000
```
(No abrir `index.html` con doble clic: los `.json` se cargan con `fetch` y necesitan un servidor.)
