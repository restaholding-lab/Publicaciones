## 📚 Estructura de publicaciones

Este repositorio funciona como catálogo de documentos HTML publicados vía GitHub Pages.
El punto de entrada es siempre `index.html`, que enlaza a cada documento agrupado por serie.

### Grupos actuales

**01 · Curso MIT para Dirección Comercial**
| Vol. | Archivo | Contenido |
|---|---|---|
| I | `ecosistema-digital.html` | Mapa interactivo del ecosistema digital por capas |
| II | `programar1.html` | Guía para construir tu primera herramienta con IA |

**02 · Hermes Enterprise Shield**
| # | Archivo | Contenido |
|---|---|---|
| 01 | `hermes_endpoint_agent.html` | Especificación técnica del Endpoint Agent |
| 02 | `hermes_diccionario_guia.html` | Traducción comercial de los términos técnicos |
| 03 | `Hermes_Shield_Neural_Skills.html` | Visualización interactiva de skills gobernadas |

### Procedimiento para publicar un documento nuevo

1. **Sube el `.html`** al repo — arrastrándolo directamente sobre esta página, o vía *Add file → Upload files*. Sin espacios en el nombre (usa `-` o `_`).
2. **Decide su grupo**: ¿es un nuevo volumen del Curso MIT, un documento de un producto existente (Hermes u otro), o el primero de una serie nueva?
3. **Añade su tarjeta en `index.html`**: copia la plantilla que hay comentada al final del propio archivo (hay una variante para "volumen numerado" y otra para "documento de producto"), y pégala antes del bloque `<div class="next">`.
4. **Actualiza el contador** ("N documentos · N series") y la fecha en la cabecera de `index.html`.
5. **Commit** y espera al check ✅ verde en la pestaña *Actions* antes de darlo por publicado.
6. **Verifica en modo incógnito** — la CDN de GitHub Pages cachea unos minutos, así que en tu navegador normal puede tardar en verse aunque ya esté publicado.

> Pendiente de limpieza: el archivo `prueba` (sin extensión) es un resto de pruebas y puede borrarse.