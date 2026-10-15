# Imprimir Amigos

App web (PWA) de Amigos for Christ para imprimir fotos en las impresoras Bixolon (SPP-R200III y similares) por Bluetooth desde teléfonos Android, en sustitución de BIXOLON mPrint.

## Cómo se usa
1. Abrir la app en Chrome para Android.
2. Tocar conectar y elegir la impresora Bixolon (debe estar emparejada por Bluetooth, PIN 0000).
3. Elegir la foto y tocar imprimir. La app ajusta sola el tamaño y la nitidez.

También se puede instalar en la pantalla de inicio y funciona sin internet. Se pueden enviar fotos desde la galería con el botón Compartir.

## Requisitos
- Android con Google Chrome (no funciona en iPhone/iPad).
- Permisos de Chrome: Dispositivos cercanos y Ubicación.

## Archivos
- index.html: la app completa.
- sw.js: modo sin conexión y recepción de fotos compartidas.
- manifest.webmanifest, icon-192.png, icon-512.png: instalación como app.
