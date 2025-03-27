# AF-PL-300

## ENLACES LABORATORIOS

- https://learn.microsoft.com/es-es/training/modules/get-data/lab-prepare

## DOCUMENTACION

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
- Implementar dimensiones realizadoras de roles: https://learn.microsoft.com/es-es/power-bi/guidance/star-schema
- Definir la cardinalidad de una relación y la dirección del filtro cruzado: https://learn.microsoft.com/es-es/power-bi/guidance/relationships-bidirectional-filtering
- Creación de una tabla de fechas común: https://learn.microsoft.com/es-es/power-bi/guidance/model-date-tables
- Implementar roles de seguridad de nivel de fila: https://radacad.com/dynamic-row-level-security-with-power-bi-made-simple


### Crear cálculos de modelos mediante DAX

- Crear medidas de agregación únicas: https://biist.pro/diferencia-columna-calculada-medida-power-bi-cual-deberias-usar-y-porque
- Usar CALCULATE para manipular filtros: https://interactivechaos.com/es/manual/tutorial-de-dax/contexto-de-fila-0
- Implementar medidas de inteligencia de tiempo: https://www.red-gate.com/simple-talk/databases/sql-server/bi-sql-server/creating-time-intelligence-functions-in-dax/
- Identificar medidas implícitas y reemplazar por medidas explícitas: https://powerbibogota.wordpress.com/2021/05/07/powerbi-calculos-o-medidas-implicitas-y-explicitas/
- Usar funciones estadísticas básicas: https://learn.microsoft.com/es-es/dax/statistical-functions-dax
- Creación de medidas de suma parcial: https://www.linkedin.com/pulse/medidas-semi-aditivas-dax-miguel-angel-franco-garc%C3%ADa/
- Crear una medida mediante medidas rápidas: https://powerbisp.com/paso-a-paso-para-analizar-y-crear-una-medida-compleja-en-dax-desmitificando-calculate
- Crear tablas calculadas: https://aglaia.es/blog/power-bi/crear-una-tabla-calculada-en-power-bi/

### Optimizar el rendimiento del modelo

- Mejorar el rendimiento mediante la identificación y eliminación de filas y columnas innecesarias: https://vandalytic.com/trucos-para-mejorar-el-rendimiento-de-tus-informes-de-power-bi/
- Identificar medidas, relaciones y objetos visuales con un rendimiento deficiente mediante el Analizador de rendimiento: https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-performance-analyzer
- Mejorar el rendimiento mediante la elección de tipos de datos óptimos: https://vandalytic.com/trucos-para-mejorar-el-rendimiento-de-tus-informes-de-power-bi/
- Mejorar el rendimiento mediante el resumen de datos

## Visualizar y analizar los datos (25-30 %)

### Crear informes

- Identificar e implementar visualizaciones adecuadas
- Formato y configuración de visualizaciones
- Usar un objeto visual personalizado
- Aplicar y personalizar un tema
- Configuración del formato condicional
- Aplicar criterios de segmentación y filtrado
- Configurar la página del informe
- Usar la característica Analizar en Excel
- Elegir cuándo usar un informe paginado

### Mejorar los informes para la facilidad de uso y la narración

- Configurar marcadores
- Crear información personalizada sobre herramientas
- Editar y configurar interacciones entre objetos visuales
- Configurar la navegación de un informe
- Aplicar ordenación
- Configurar segmentaciones de sincronización
- Agrupar y superponer objetos visuales mediante el panel Selección
- Explorar en profundidad los datos mediante objetos visuales interactivos
- Configurar la exportación del contenido del informe y realizar una exportación
- Diseñar informes para dispositivos móviles
- Habilitación de objetos visuales personalizados en un informe
- Diseño y configuración de informes accesibles de Power BI

### Identificar patrones y tendencias

- Usar la característica Analizar en Power BI
- Usar la agrupación, la discretización y la agrupación en clústeres
- Incorporar la característica Preguntas y respuestas en un informe
- Uso de objetos visuales de IA
- Usar líneas de referencia, barras de error y previsión
- Detectar valores atípicos y anomalías
- Crear y compartir cuadros de mandos y métricas

## Implementar y mantener elementos (15–20 %)

### Crear y administrar áreas de trabajo y recursos

- Crear y configurar un área de trabajo
- Asignación de roles de área de trabajo
- Configurar y actualizar una aplicación de área de trabajo
- Publicación, importación o actualización de elementos en un área de trabajo
- Crear paneles
- Elegir un método de distribución
- Aplicar etiquetas de confidencialidad al contenido del área de trabajo
- Configurar suscripciones y alertas de datos
- Promover o certificar contenido de Power BI
- Administrar opciones globales para archivos

### Administración de modelos semánticos

- Identificar cuándo se requiere una puerta de enlace
- Configuración de una actualización programada de modelo semántico
- Configurar la pertenencia a grupos de seguridad de nivel de fila
- Proporcionar acceso a los modelos semánticos
- Configuración de la actualización automática de páginas
