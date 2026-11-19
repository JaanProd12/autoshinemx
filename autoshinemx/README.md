# AUTOSHINE: sitio web

Sitio estático (un solo `index.html`, sin framework ni compilación).

- Carpeta que se publica: `public`
- Comando de compilación: ninguno (dejar vacío)
- Archivo de entrada: `public/index.html`

Precios, contacto, equipo y galería se editan en el bloque `CONFIG` al inicio del `<script>` de `public/index.html`.

## Cloudflare (flujo con Workers)

`wrangler.jsonc` en la raíz indica que se publica la carpeta `public`. El campo `name` debe coincidir con el nombre del proyecto en Cloudflare (`autoshinemx`). Build command: vacío. Deploy command: `npx wrangler deploy`.
