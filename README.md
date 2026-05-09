# NOV MD Totco · Guía de Incidentes (v2)

## Novedades de esta versión
- ⭐ **Sistema de favoritos**: tocá la estrella al lado del subcódigo para guardarlo
- 📌 **Pestaña "Favoritos"**: nueva pestaña con todos los subcódigos guardados
- 🎨 **Logo NOV oficial** en el ícono de la app
- 🔄 **Actualización automática** en celulares ya instalados (gracias al cambio de versión del Service Worker)

## Cómo subir esta actualización al repositorio existente

1. Ir a https://github.com/childrenbill-jpg/guia-tecnicos-nov (o el nombre que le hayas puesto al repo)
2. Click en cada archivo viejo y reemplazarlo por el nuevo:
   - `index.html` ← reemplazar
   - `sw.js` ← reemplazar (importante para forzar actualización)
   - `icon-192.png` ← reemplazar (ahora tiene el logo NOV)
   - `icon-512.png` ← reemplazar (ahora tiene el logo NOV)
   - `manifest.json` ← reemplazar (sin cambios pero por las dudas)
3. O más fácil: borrar todos los archivos del repositorio y subir los nuevos arrastrando.

## Cómo renombrar el repositorio a "guia-tecnicos-nov"

1. Ir al repositorio en GitHub.
2. Click en **Settings** (engranaje arriba a la derecha).
3. En la primera sección "Repository name" cambiar `nov-md-totco-guia` por `guia-tecnicos-nov`.
4. Click en **Rename**.
5. Tu nueva URL será: **https://childrenbill-jpg.github.io/guia-tecnicos-nov/**
6. La URL vieja seguirá redirigiendo automáticamente al nuevo nombre por un tiempo, pero conviene actualizar el link compartido.

## Para los técnicos que ya instalaron la app
La próxima vez que abran la app con internet, automáticamente se descargará la versión nueva con favoritos y logo. Si no se actualiza al instante, basta con cerrar y abrir la app de nuevo.
