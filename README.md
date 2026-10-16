# nephei-portal

Portada de [nephei.org](https://nephei.org): una página estática con enlaces a las secciones del sitio.

## Estructura

- `public/`: lo que se publica tal cual. `index.html` es la portada.
- `wrangler.jsonc`: configuración del Worker `nephei-portal` (solo assets estáticos, sin código de servidor).

## Despliegue

El repositorio está conectado al Worker `nephei-portal` con Workers Builds: cada push a `main` lo despliega. Sirve `nephei.org` y `www.nephei.org` como dominios personalizados.
