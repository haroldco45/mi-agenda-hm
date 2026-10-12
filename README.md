# Mi Agenda HM

Página de venta de la app de citas de Vibras Positivas HM para negocios que trabajan con cita: uñas, barberías, peluquerías, cejas y pestañas, estética y spa.

Desarrollada por **Vibras Positivas HM** — Derechos de Autor Reservados.

## Qué tiene

- Héroe con el celular mostrando cómo la clienta escoge día y hora.
- Los tres problemas que resuelve, cómo reserva la clienta y lo que maneja la dueña.
- Calculadora de horas ahorradas al mes.
- Botón a la demo en vivo: `https://cita-unas.netlify.app/?demo` (PIN de administración de la demo: `1234`).
- Formulario que abre WhatsApp al 311 770 0431 con el mensaje listo.
- PWA instalable, con íconos y la imagen para compartir de 1200×630.

## Archivos

| Archivo | Para qué |
|---|---|
| `index.html` | La página |
| `manifest.json` | Instalación como app |
| `sw.js` | Funciona sin internet |
| `icon-192.png`, `icon-512.png` | Íconos de la app |
| `og-image.png` | Imagen al compartir el enlace por WhatsApp |

## Publicación

1. Crear el repositorio `haroldco45/mi-agenda-hm` y subir todos los archivos a la raíz.
2. En Settings > Pages, publicar desde la rama `main`, carpeta raíz.
3. La página queda en `https://haroldco45.github.io/mi-agenda-hm/`.
4. En Netlify, importar el mismo repositorio sin comando de compilación. Se actualiza solo con cada cambio en GitHub.

Si el repositorio queda con otro nombre, cambiar `mi-agenda-hm` en las etiquetas `og:url`, `og:image` y `twitter:image` del `index.html`.

## Actualizaciones

Al cambiar `index.html`, subir la versión en `sw.js` (`mi-agenda-hm-v1` → `mi-agenda-hm-v2`) para que los celulares que ya la instalaron tomen el cambio.
