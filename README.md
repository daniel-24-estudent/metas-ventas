# Mis metas de ventas (app instalable)

Contenido de esta carpeta: `index.html` (la app), `manifest.webmanifest`, `sw.js` (para que funcione sin internet) e íconos. **No subas a GitHub ningún Excel de clientes ni copias de seguridad**: la app guarda los datos solo en el aparato de quien la usa.

## Publicar en GitHub Pages (una sola vez, unos 10 minutos)

1. Crea una cuenta gratis en https://github.com (si no tienes).
2. Arriba a la derecha: **+ → New repository**. Nombre sugerido: `metas-ventas`. Déjalo en **Public** y pulsa **Create repository**.
3. En la página del repositorio pulsa **uploading an existing file**. Descomprime el .zip en tu PC y arrastra **los archivos** (no la carpeta): `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`. Pulsa **Commit changes**.
4. Ve a **Settings → Pages**. En *Build and deployment*, elige **Deploy from a branch**, rama **main**, carpeta **/ (root)** y **Save**.
5. Espera 1 o 2 minutos y recarga. Arriba aparecerá la dirección: `https://TU-USUARIO.github.io/metas-ventas/`

## Instalar la app

- **PC (Chrome o Edge):** abre la dirección y pulsa el ícono de instalar en la barra de direcciones (o el botón "📲 Instalar como app" al final de la página). Queda con su ícono y se abre en su propia ventana.
- **Android (Chrome):** abre la dirección, menú ⋮ → **Instalar app** (o *Agregar a la pantalla principal*).

Después de abrirla una vez con internet, funciona sin conexión.

## Datos y copia de seguridad

- Los datos de la PC y del celular **son independientes**. Para pasar los datos de uno a otro: en el primero pulsa **⬇ Guardar copia** (baja un archivo `.json`), pásalo por WhatsApp o correo y en el otro usa **Restaurar copia**. Restaurar reemplaza lo que haya en ese aparato.
- Guarda una copia seguido (por ejemplo cada semana). Si se borran los datos del navegador, sin copia se pierde todo.

## Actualizar la app

Si cambias `index.html` en GitHub (Add file → Upload files, mismo nombre), la app se actualiza sola en la siguiente apertura con internet. Si no se nota el cambio, cierra y vuelve a abrir la app.
