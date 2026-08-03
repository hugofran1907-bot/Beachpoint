# Beach Point Cambrils — Página Web

Sitio web estático para Beach Point (Cambrils), con dos páginas:

- `index.html` — Página de inicio (historia, servicios, reseñas, contacto y mapa)
- `carta.html` — Carta completa de bebidas y comida

No necesita instalación ni build: es HTML puro con Tailwind cargado desde CDN.

## Cómo subirlo a GitHub y publicarlo (GitHub Pages)

1. Entra en [github.com](https://github.com) y crea un repositorio nuevo (por ejemplo `beach-point-web`). Puede ser público.
2. En tu ordenador, descomprime esta carpeta y sube los archivos al repositorio. Las dos formas más fáciles:
   - **Desde la web de GitHub:** abre el repositorio → botón "Add file" → "Upload files" → arrastra `index.html`, `carta.html` y `README.md` → "Commit changes".
   - **Desde terminal:**
     ```bash
     git init
     git add .
     git commit -m "Primera versión del sitio Beach Point"
     git branch -M main
     git remote add origin https://github.com/TU_USUARIO/beach-point-web.git
     git push -u origin main
     ```
3. Ve a **Settings → Pages** en el repositorio.
4. En "Source", elige la rama `main` y la carpeta `/root`, luego guarda.
5. Espera 1-2 minutos: GitHub te dará una URL del tipo `https://TU_USUARIO.github.io/beach-point-web/`.

## Notas

- Las imágenes actuales están enlazadas desde una URL externa de Google (usadas solo como ejemplo/placeholder). Para producción, lo ideal es sustituirlas por fotos reales de Beach Point subidas a una carpeta `images/` del repositorio, y cambiar el `src` de cada `<img>` por, por ejemplo, `images/hero.jpg`.
- Los datos de contacto, dirección y horarios en `index.html` ya están puestos según lo indicado (Avinguda Diputació 18, Cambrils).
