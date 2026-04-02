# CalculadoraBarba

Calculadora offline para viajeros.

## Cómo usar en Android (sin instalar en PC)

1. Copia `index.html` al teléfono.
2. Ábrelo con Chrome (o navegador compatible).
3. La app funciona 100% offline.

## Funciones

- Cálculo por producto:
  - `resultado = (precio_peso_mx * factor) + (base * peso_producto)`
- Valores por defecto personalizables:
  - `factor = 30.5`
  - `base = 10400`
- Crear y seleccionar viajes.
- Guardar productos por viaje.
- Listar productos guardados por viaje.
- Mostrar total acumulado del viaje (suma de resultados).
- Exportar un viaje a archivo JSON.
- Importar un viaje desde archivo JSON.

## Persistencia

Los datos se guardan localmente en el navegador del móvil (`localStorage`).

## Respaldo y restauración (JSON)

1. Selecciona un viaje.
2. Pulsa `Exportar viaje JSON`.
3. El navegador descargará un archivo `.json`.
4. Para recuperar, pulsa `Importar viaje JSON` y selecciona ese archivo.

Notas:
- El viaje importado se agrega como nuevo viaje.
- Si ya existe un viaje con el mismo nombre, se renombra automáticamente para evitar conflictos.
