Estructura de metadata (nota técnica)

Esta app está diseñada para ejecutarse como HTML offline en navegador móvil.
Por seguridad del navegador, no puede crear carpetas y archivos físicos automáticos
como metadata/viaje/producto dentro del teléfono.

En su lugar, la app guarda toda la estructura de viajes y productos en el
almacenamiento local del navegador (localStorage), de forma persistente y offline.

Estructura lógica interna equivalente:
- metadata
  - viaje
    - producto (con todos los campos del cálculo)

Respaldo:
- Se puede exportar un viaje a archivo JSON.
- Se puede importar un viaje JSON para restaurarlo en el dispositivo.
