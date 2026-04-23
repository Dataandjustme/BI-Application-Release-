# Preparación de Datos (Excel / Power Query)

## Objetivo
Realizar limpieza, corrección y perfilado de datos para asegurar consistencia antes del análisis en Python.

## Datasets cargados
- Inventarios.csv
- Márgenes.csv
- Costos.csv
- Ventas.csv

## Pasos realizados
- **Carga de datos**: importación de los cuatro datasets en Power Query.
- **Corrección de datos**:
  - Ajuste de tipos de columnas (fechas, numéricos, texto).
  - Normalización de nombres de variables.
- **Limpieza**:
  - Eliminación de duplicados.
  - Tratamiento de valores nulos.
  - Filtrado de registros inconsistentes.
- **Data profiling**:
  - Revisión de distribución de valores.
  - Identificación de outliers.
  - Validación de integridad de claves (Producto, Presentación, Fecha).
- **Ordenamiento y estructuración**:
  - Organización de columnas.
  - Preparación de datasets finales para análisis multivariado.

## Resultado
Se obtuvieron datasets limpios y estructurados, listos para análisis en Python.  
Esto asegura trazabilidad y reproducibilidad en el flujo DataOps: **Preparación (Excel) → Análisis (Python) → Visualización (Charts) → Documentación (Markdown)**.

