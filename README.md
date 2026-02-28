# Calculadora JPrinter3D para GitHub Pages

Esta carpeta ya está lista para subirla a **GitHub** y publicarla con **GitHub Pages**.

## Archivos
- `index.html` → app principal
- `manifest.webmanifest` → configuración para instalarla como acceso directo
- `icon-180.png`, `icon-192.png`, `icon-512.png` → íconos
- `.nojekyll` → evita problemas de publicación en GitHub Pages

## Cómo publicarla
1. Crea un repositorio nuevo en GitHub.
2. Sube todos estos archivos a la raíz del repositorio.
3. En GitHub entra a:
   **Settings → Pages**
4. En **Build and deployment**, selecciona:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Guarda los cambios.
6. GitHub te dará una URL parecida a:
   `https://tuusuario.github.io/nombre-del-repo/`

## Cómo agregarla al iPhone
1. Abre la URL publicada en **Safari**.
2. Toca **Compartir**.
3. Elige **Agregar a pantalla de inicio**.

## Recomendación
Si quieres que la app cargue incluso sin internet, después te puedo preparar una versión con **service worker** para modo offline.
