# NOV MD Totco · Guía de Incidentes (PWA)

Guía interactiva de categorización de incidentes en español/inglés.

## Cómo publicar (gratis, 5 minutos) — GitHub Pages

### Paso 1: Crear cuenta en GitHub
1. Ir a https://github.com y registrarse (es gratis, solo email).

### Paso 2: Crear el repositorio
1. Click en el botón verde "**New**" o ir a https://github.com/new
2. Nombre del repositorio: `nov-md-totco-guia` (o lo que prefieras).
3. Marcar como "**Public**".
4. Click "**Create repository**".

### Paso 3: Subir los archivos
1. En la página del repositorio, click "**uploading an existing file**" (o arrastrar los archivos).
2. Subir los 5 archivos de esta carpeta:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Click "**Commit changes**".

### Paso 4: Activar GitHub Pages
1. En el repositorio, ir a **Settings** (engranaje arriba a la derecha).
2. En el menú lateral izquierdo, click "**Pages**".
3. En "Source", elegir: Branch = `main`, Folder = `/ (root)`.
4. Click "**Save**".
5. Esperar 1-2 minutos. GitHub te mostrará una URL del estilo:
   `https://TU_USUARIO.github.io/nov-md-totco-guia/`

### Paso 5: Compartir e instalar
1. Mandar la URL por WhatsApp/email a los técnicos.
2. En el celular, abrir la URL con **Chrome (Android)** o **Safari (iPhone)**.
3. **Android (Chrome):** aparecerá un banner "Instalar app" o ir a menú ⋮ → "**Instalar app**" / "**Agregar a pantalla de inicio**".
4. **iPhone (Safari):** tocar el botón Compartir 📤 → "**Agregar a pantalla de inicio**".
5. Listo: queda como app con el ícono rojo NOV. Funciona offline una vez instalada.

## Alternativas a GitHub Pages
- **Netlify Drop** (https://app.netlify.com/drop): aún más simple, arrastrar la carpeta y listo.
- **Cloudflare Pages**, **Vercel**: también gratis.

## Actualizar la app
Si querés actualizar el contenido (nuevos términos, etc.):
1. Reemplazás `index.html` en GitHub.
2. **Importante:** abrí `sw.js` y cambiá la línea `const CACHE_NAME = 'nov-mdtotco-v1';` por `'nov-mdtotco-v2'` (sumá un número). Esto fuerza a los celulares a actualizar.
3. Los técnicos verán los cambios la próxima vez que abran la app con internet.

## Soporte
Esta PWA funciona offline. La primera vez requiere internet para descargarse; después funciona sin conexión.
