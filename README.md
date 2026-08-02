# Radar Global 24 — sitio web

## Estructura

```
index.html              -> página de inicio (secciones: Mundial, Regional, Profesiones, Especiales)
css/style.css            -> estilos de todo el sitio (colores, tipografía, tarjetas)
img/logo.jpg              -> tu logo oficial
img/portada.jpg            -> tu imagen de portada
posts/                      -> una página HTML por cada publicación
```

## Cómo publicarlo gratis (GitHub Pages)

1. Crea una cuenta gratuita en https://github.com si no tienes una.
2. Crea un repositorio nuevo, por ejemplo `radarglobal24`.
3. Sube todos los archivos y carpetas de esta entrega (index.html, css/, img/, posts/) tal cual, respetando la estructura de carpetas.
4. En el repositorio, ve a Settings -> Pages -> Branch: main -> Save.
5. En un par de minutos tu web quedará publicada en una dirección tipo:
   https://tu-usuario.github.io/radarglobal24/

## Flujo diario para agregar contenido nuevo

Cada día que quieras publicar una nueva edición:

1. Abre un chat conmigo y pídeme, por ejemplo: "Genera el Radar Regional de hoy para la web".
2. Te entrego un nuevo archivo HTML de artículo (como `posts/radar-regional-2026-08-03.html`) más la infografía correspondiente.
3. Subes ese archivo nuevo a la carpeta `posts/` de tu repositorio.
4. Agregas una tarjeta nueva en `index.html`, en la sección correspondiente, copiando el bloque `<a class="post-card">...</a>` de un ejemplo existente y cambiando el título, la fecha, el resumen y el enlace `href` al nuevo archivo.
5. Subes los cambios (o los pegas directo en GitHub) y la web queda actualizada.

Si en algún momento quieres que te arme también el paso 3-4-5 como un archivo lote (script), lo puedo preparar, pero seguirá siendo un proceso que tú disparas — no ocurre solo.
