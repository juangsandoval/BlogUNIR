# Mi Blog Jekyll

Ejemplo mínimo de blog estático con Jekyll, HTML y CSS.

## Estructura

- `_config.yml`: configuración general del sitio.
- `_layouts/default.html`: plantilla principal.
- `_layouts/post.html`: plantilla para entradas del blog.
- `_posts/`: entradas del blog.
- `assets/css/styles.css`: estilos CSS.
- `assets/img/`: imágenes usadas en las entradas.
- `index.html`: página principal.
- `about.html`: página acerca del blog.

## Cómo ejecutarlo localmente

Instala Ruby y Bundler. Luego, dentro de la carpeta del proyecto, ejecuta:

```bash
bundle install
bundle exec jekyll serve
```

Después abre en el navegador:

```text
http://localhost:4000
```

## Cómo publicarlo en GitHub Pages

1. Sube esta carpeta a un repositorio de GitHub.
2. Ve a Settings > Pages.
3. Selecciona la rama principal.
4. Si tu repositorio se llama, por ejemplo, `mi-blog-jekyll`, cambia en `_config.yml`:

```yml
baseurl: "/mi-blog-jekyll"
```
