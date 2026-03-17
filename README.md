# Portfolio estático para GitHub Pages

Este repositorio contiene un sitio estático (HTML + CSS) listo para publicar en GitHub Pages.

Cómo usar

- Personaliza tu nombre, correo y enlaces editando `index.html`.
- Reemplaza los enlaces de los proyectos por tus repositorios.

Opciones de despliegue en GitHub Pages

Opción A — Publicar en la URL `https://USERNAME.github.io` (recomendado para portafolio personal):

1. Crea un repositorio en GitHub llamado `USERNAME.github.io` (sustituye `USERNAME`).
2. Desde la carpeta del proyecto:

```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin git@github.com:USERNAME/USERNAME.github.io.git
git push -u origin main
```

GitHub Pages publicará automáticamente el contenido desde la rama `main` en la raíz.

Opción B — Usar Pages en un repositorio normal (por ejemplo `username/portfolio`):

1. Crea un repositorio normal.
2. Sube el contenido y en la configuración del repositorio (Settings → Pages) selecciona la rama `main` y la carpeta `/root` o la carpeta `docs/` si prefieres mover los archivos allí.

Personalización

- Cambia el título en `index.html` (etiqueta `<title>`).
- Actualiza el correo en la sección de contacto (`mailto:`).
- Añade más tarjetas en la sección `#projects` para listar tus trabajos.

¿Quieres que haga el commit por ti y prepare el repositorio remoto? Dime tu nombre de usuario de GitHub y puedo generar los comandos listos para copiar-pegar.
