# Los momentos de Syneb

Diario de momentos felices. Funciona como app instalable (PWA) y sin internet.
Los recuerdos se guardan solo en el celular de quien la usa.

## Publicar en GitHub Pages
1. Crea una cuenta en github.com (si no tienes) y toca **New repository**. Nómbralo, por ejemplo, `Syneb`. Déjalo **Public**.
2. En el repositorio toca **uploading an existing file** y arrastra TODO el contenido de esta carpeta
   (`index.html`, `manifest.json`, `sw.js` y la carpeta `icons`). Toca **Commit changes**.
3. Ve a **Settings → Pages**. En *Source* elige **Deploy from a branch**, rama **main**, carpeta **/ (root)**, y **Save**.
4. En 1 o 2 minutos tu app estará en `https://TU-USUARIO.github.io/Syneb/`.

## Instalar en el celular
- iPhone: abrir el enlace en Safari → Compartir → **Agregar a inicio**.
- Android: abrir en Chrome → ⋮ → **Instalar app** o **Agregar a pantalla de inicio**.
Abrir la app una vez con internet para que quede lista sin conexión.

## Actualizar la app
Cuando cambies `index.html`, sube también `sw.js` con el número de `VERSION` cambiado
(`Syneb-v2`, `Syneb-v3`...). Así los celulares reciben la versión nueva.

## Importante
- No subas aquí archivos de respaldo (`Syneb-respaldo-*.json`): el repositorio es público.
- Guarda respaldos seguido (Drive, Archivos, WhatsApp). Si se borran los datos del navegador, solo el respaldo los recupera.
- Pasar recuerdos de la versión anterior: Guardar respaldo allá y Restaurar aquí.
