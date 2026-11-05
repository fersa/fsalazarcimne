# Web personal de Fernando Salazar González

Sitio Jekyll listo para GitHub Pages. GitHub lo compila solo: no hace falta instalar nada.

## Publicarlo

1. Crea un repositorio público llamado `TUUSUARIO.github.io`.
2. Sube todo el contenido de esta carpeta (botón "Add file → Upload files", arrastrando las carpetas).
3. Ve a Settings → Pages, elige "Deploy from a branch", rama `main`, carpeta `/ (root)` y guarda.
4. En uno o dos minutos la web estará en `https://TUUSUARIO.github.io`.

Si el repositorio tiene otro nombre (por ejemplo `web`), edita `_config.yml` y pon `baseurl: "/web"`.

## Fotos

Descarga tus fotos de la web de Google Sites (clic derecho → Guardar imagen) y súbelas a `assets/img/` como:
- `profile.jpg`: foto pequeña y redonda de la barra lateral.
- `home.jpg`: foto grande de la portada.

## Editar el contenido

Cada página es un archivo Markdown en la raíz (`about.md`, `projects.md`...) y las publicaciones están en `publications/`. Puedes editarlos directamente en GitHub con el icono del lápiz; al guardar, la web se actualiza sola.

- Lista numerada: `1. Texto`
- Enlace: `[texto](https://url)`
- Sección: `## Título`

El menú se cambia en `_data/navigation.yml` y los colores y tipografías en `assets/css/style.css`.
