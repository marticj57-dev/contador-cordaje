CONTADOR DE CORDAJE DE TENIS — VERSIÓN 3

Archivos: index.html, manifest.json, sw.js y este README.

Novedades:
- Duraciones cada 30 minutos, de 30 min a 10 h, mostradas en formato legible.
- Editar la fecha y la duración de una sesión.
- Gráfico de barras: Raqueta 1 naranja y Raqueta 2 azul.
- Totales y gráfico se actualizan al añadir, editar o borrar sesiones.
- Se conserva la clave localStorage `contadorCordajeTenis_v1` para mantener los datos de versiones anteriores compatibles.

ACTUALIZACIÓN EN GITHUB PAGES
1. Antes de actualizar, abre la app actual y pulsa Exportar datos.
2. Descomprime este ZIP y sustituye en tu repositorio index.html, manifest.json y sw.js.
3. Publica los cambios en la misma rama/carpeta de GitHub Pages.
4. Abre la app con el mismo navegador y dominio que utilizabas antes.
5. Comprueba los totales. Si no aparece la nueva versión, cierra y vuelve a abrir la aplicación o recarga la página.

IMPORTANTE
Los datos se guardan en el almacenamiento local del navegador/dispositivo, no en GitHub. Exporta copias periódicamente. Al pulsar “Cordaje roto”, se archivan las sesiones del cordaje anterior y el contador de esa raqueta vuelve a cero.
