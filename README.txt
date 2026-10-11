CONTADOR DE CORDAJE DE TENIS — PRIMERA VERSIÓN

Contenido:
- index.html: aplicación.
- manifest.json: configuración para instalarla como PWA.
- sw.js: funcionamiento básico sin conexión después de la primera carga.

FUNCIONES
- Dos raquetas con nombres editables.
- Introducción de minutos por sesión.
- Acumulación automática de tiempo y sesiones.
- Al romperse el cordaje, guarda la duración en el historial y reinicia ese contador.
- Exportación e importación de copia de seguridad en JSON.

IMPORTANTE
Los datos se guardan en el almacenamiento local del navegador del teléfono. Exporta copias de seguridad periódicamente. Si borras los datos del navegador, puedes perder el historial.

PARA USARLA EN ANDROID
Una PWA necesita servirse desde una dirección HTTPS para poder instalarse correctamente y utilizar el service worker. No basta con abrir el archivo HTML directamente.
1. Publica los tres archivos en un alojamiento estático HTTPS (por ejemplo, GitHub Pages).
2. Abre la dirección HTTPS en Chrome en tu Android.
3. Menú ⋮ > “Instalar aplicación” o “Añadir a pantalla de inicio” (el texto puede variar).
4. Abre la aplicación instalada y prueba a registrar una sesión.
5. Usa “Exportar copia de seguridad” para guardar una copia periódica.

Esta primera versión no sincroniza datos entre móviles y no tiene una base de datos en la nube.
