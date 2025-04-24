# **Limpieza y Estandarización de Datos - Proyecto de Preprocesamiento**

## Descripción

Este proyecto consiste en el tratamiento y limpieza de un conjunto de datos que presentaba inconsistencias en los formatos, valores duplicados y datos nulos. Se aplicaron técnicas de estandarización, corrección de formatos y análisis de valores faltantes para dejar el dataset listo para su análisis exploratorio y modelado futuro.

## Librerías utilizadas

- Pandas
- Seaborn / Matplotlib (visualización de datos)


## Proceso realizado

1. **Inspección inicial del dataset**  
   Se identificaron columnas con formatos inconsistentes y presencia de valores nulos.

2. **Limpieza de columnas de texto**
   - Unificación de términos (ej. `trans` a `transferencia`).
   - Aplicación de formato título para nombres propios (`nombre` y `apellido`).
    
4. **Corrección de formatos de fecha**  
   - Detección de distintos formatos de fecha.
   - Conversión a `datetime` usando `pd.to_datetime` con manejo de errores.
   - Creación de columna unificada y eliminación de columnas auxiliares.

5. **Análisis de valores nulos**  
   - Exploración de correlación entre datos faltantes.
   - Visualización con heatmap.
   - Etiquetado como `desconocido` en casos sin correlación, dado que representaban un 33% de los datos y no podían eliminarse.

## Resultados

Se obtuvo un dataset limpio, estandarizado y coherente, listo para ser utilizado en análisis posteriores y en la toma de decisiones basada en datos confiables.


##  Autor

Ana Herrera Chuica  
Estudiante de Ingeniería Industrial | Aspirante a Analista de Datos

www.linkedin.com/in/anaherrerachuica
