# Examen auxiliar administrativo C2

Práctica para la oposición de auxiliar administrativo, grupo C2, del Servizo Galego de Saúde (Sergas). La portada enlaza las dos leyes. La respuesta de cada pregunta permanece oculta hasta que pulsas «Mostrar respuesta».

Cada página de ley tiene 60 preguntas tipo test. El botón «Mostrar respuesta» cita el artículo del texto consolidado del BOE.

## Requisitos

- [Hugo](https://gohugo.io/) 0.158.0 o posterior. Este sitio se ha comprobado con Hugo v0.165.0 extended.
- Git, para descargar el tema.

## Tema

[PaperMod](https://github.com/adityatelange/hugo-PaperMod), submódulo en `themes/PaperMod`, fijado al commit `26523e0`. La etiqueta v8.0 no construye con Hugo 0.165: el tema pasó los parciales a `layouts/_partials` y no hay una etiqueta posterior.

## Arranque

```bash
git submodule update --init --recursive
hugo server
```

Abre la dirección que imprime Hugo. En local suele ser http://localhost:1313/.

## Construcción

```bash
hugo --minify
```

El HTML queda en `public/`. Esa carpeta no se versiona.
