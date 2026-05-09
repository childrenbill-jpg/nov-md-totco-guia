# NOV MD Totco · Guía de Incidentes (v3)

## Novedades de esta versión
- 📋 **Campo Work Order (WO)** arriba del formulario, siempre visible
- 📤 **Botón "Compartir al supervisor"**: abre el menú nativo del celular para elegir WhatsApp/email/contacto, con mensaje predeterminado:
  ```
  ✅ WO-XXXXX completada en RESCO
  
  📋 Detalle del incidente:
  • Category: ...
  • Type: ...
  • Code: ...
  • Sub: ...
  ```
- 📜 **Pestaña "Historial"**: guarda automáticamente las **últimas 5 WO** que se compartieron, con botones para reenviar, recargar al formulario o eliminar
- 🔄 Service Worker actualizado a v3 (los celulares con la app instalada se actualizan solos)

## Cómo subir esta actualización al repositorio
1. Ir a https://github.com/childrenbill-jpg/nov-md-totco-guia (o el nombre actual del repo)
2. Click en **Add file → Upload files**
3. Arrastrar los 5 archivos del ZIP
4. **Commit changes**
5. Esperar 1-2 minutos
6. Probar con Ctrl+F5 en https://childrenbill-jpg.github.io/nov-md-totco-guia/

## Cómo funciona el botón Compartir
- En el celular: abre el menú nativo del sistema. El técnico elige WhatsApp, contacto, etc.
- En PC: abre WhatsApp Web con el mensaje listo para enviar.
- Cuando se comparte exitosamente, la WO se guarda automáticamente en el historial.
