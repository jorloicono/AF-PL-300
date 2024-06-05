# AF-PL-300

- GUIA DE ESTUDIO: https://learn.microsoft.com/es-es/credentials/certifications/resources/study-guides/pl-300
- RUTAS DE APRENDIZAJE: https://learn.microsoft.com/es-es/training/courses/pl-300t00
- REPOSITORIO LABORATORIOS OFICIALES: https://microsoftlearning.github.io/PL-300-Microsoft-Power-BI-Data-Analyst/

## Preparar los datos (25-30 %)

### Obtener datos desde orígenes de datos

- Identificar un origen de datos y conectarse a él: https://www.dataxbi.com/blog/2018/10/23/conectarse-origenes-datos-power-bi-desktop-excel-2016/
- Cambiar la configuración del origen de datos, incluidas las credenciales, los niveles de privacidad y las ubicaciones del origen de datos: https://learn.microsoft.com/es-es/power-bi/connect-data/desktop-data-sources
- Selección de un modelo semántico compartido o creación de un modelo de datos local: https://learn.microsoft.com/es-es/power-bi/connect-data/desktop-report-lifecycle-datasets
- Elegir entre DirectQuery, Importar y modo dual: https://vandalytic.com/tutorial-power-bi-importar-vs-direct-query-live/
- Cambiar el valor en un parámetro: https://learn.microsoft.com/es-es/power-query/power-query-query-parameters

### Limpieza de los datos

- Evaluar datos, incluidas las estadísticas de datos y las propiedades de columna: https://learn.microsoft.com/es-es/power-query/data-profiling-tools
- Resolver incoherencias, valores inesperados o NULL e incidencias de calidad de los datos: https://learn.microsoft.com/es-es/power-query/replace-values
- Resolver errores de importación de datos: https://learn.microsoft.com/es-es/power-query/dealing-with-errors

### Transformar y cargar datos

- Seleccionar los tipos de datos de columna adecuados: https://learn.microsoft.com/es-es/power-query/data-types
- Crear y transformar columnas: https://learn.microsoft.com/es-es/power-query/add-custom-column
- Transformar una consulta
- Diseñar un esquema de estrella que contenga hechos y dimensiones
- Identificar cuándo usar consultas de referencia o duplicadas y el impacto resultante: https://tutoliber.com/diferencia-entre-duplicar-o-referenciar-una-Query
- Combinar y anexar consultas: https://learn.microsoft.com/es-es/power-query/append-queries
- Identificar y crear claves adecuadas para las relaciones: https://learn.microsoft.com/es-es/power-query/merge-queries-inner
- Configurar la carga de datos para consultas

## Modelar los datos (25-30 %)

### Diseñar e implementar un modelo de datos

- Configurar propiedades de tablas y columnas
- Implementar dimensiones realizadoras de roles
- Definir la cardinalidad de una relación y la dirección del filtro cruzado
- Creación de una tabla de fechas común
- Implementar roles de seguridad de nivel de fila: https://radacad.com/dynamic-row-level-security-with-power-bi-made-simple


### Crear cálculos de modelos mediante DAX

- Crear medidas de agregación únicas
- Usar CALCULATE para manipular filtros: https://interactivechaos.com/es/manual/tutorial-de-dax/contexto-de-fila-0
- Implementar medidas de inteligencia de tiempo
- Identificar medidas implícitas y reemplazar por medidas explícitas
- Usar funciones estadísticas básicas
- Creación de medidas de suma parcial
- Crear una medida mediante medidas rápidas
- Crear tablas calculadas

### Optimizar el rendimiento del modelo

- Mejorar el rendimiento mediante la identificación y eliminación de filas y columnas innecesarias
- Identificar medidas, relaciones y objetos visuales con un rendimiento deficiente mediante el Analizador de rendimiento
- Mejorar el rendimiento mediante la elección de tipos de datos óptimos
- Mejorar el rendimiento mediante el resumen de datos
