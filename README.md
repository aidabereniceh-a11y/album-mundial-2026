# Álbum Mundial 2026 ⚽

Generador de prompts (imagen y video) para "meterte" al Mundial 2026 con tu propia selfie. Inspirado en [placemeintheworldcup](https://crownemmanuel.github.io/placemeintheworldcup/), en español.

Sitio 100% estático — un solo archivo `index.html`, sin backend ni dependencias que instalar.

## Cómo publicarlo en GitHub Pages

### Opción A — Subir desde la web de GitHub (sin usar terminal)

1. Entra a [github.com/new](https://github.com/new) y crea un repositorio nuevo.
   - Nombre sugerido: `album-mundial-2026`
   - Márcalo como **Public**
   - No selecciones "Add a README" (ya tienes uno)
2. Dentro del repo recién creado, da clic en **"uploading an existing file"** (o el botón "Add file" → "Upload files").
3. Arrastra los dos archivos de esta carpeta: `index.html` y `README.md`.
4. Da clic en **Commit changes**.
5. Ve a **Settings → Pages** (en el menú izquierdo).
6. En "Source", elige la rama `main` y la carpeta `/ (root)`. Guarda.
7. Espera 1–2 minutos y GitHub te dará el link, algo como:
   `https://TU-USUARIO.github.io/album-mundial-2026/`

### Opción B — Desde tu PowerShell (como haces con tus otros proyectos)

```powershell
cd C:\ruta\donde\pusiste\la\carpeta\album-mundial-2026
git init
git add .
git commit -m "Primera versión del Álbum Mundial 2026"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/album-mundial-2026.git
git push -u origin main
```

Luego activa Pages igual que en la Opción A, pasos 5–7.

## Personalizar

Todo el contenido (escenas, selecciones, colores de camiseta y las plantillas de prompt) está en el bloque `<script>` al final de `index.html`, en los arreglos `TEAMS` y `SCENES`. Puedes editarlos directamente con Ctrl+A / reemplazo del archivo, como sueles hacer en tus otros proyectos.

## Créditos

Hecho por diversión, sin afiliación con la FIFA. Idea original: placemeintheworldcup.
