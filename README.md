# AUTOSHINE: sitio web

Sitio estático (un solo `public/index.html`, sin framework ni compilación).

- Carpeta que se publica: `public` (definida en `wrangler.jsonc`)
- Nombre del Worker en Cloudflare: `autoshinemx1` (debe coincidir con `name` en `wrangler.jsonc`)
- Comando de compilación: ninguno (dejar vacío)
- Comando de despliegue: `npx wrangler deploy`

Productos, precios, contacto, equipo y organigrama se editan en el bloque `CONFIG` al inicio del `<script>` de `public/index.html`.

Las fotos de producto están en `public/img/`. Para cambiar una, reemplaza el archivo con el mismo nombre o cambia `foto` del producto en `CONFIG`.
