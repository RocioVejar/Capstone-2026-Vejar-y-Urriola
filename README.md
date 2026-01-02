# Proyecto Final – CASEN 2022  
**Redes de apoyo social y experiencias de discriminación en Chile**

## Descripción
Este proyecto analiza redes de apoyo social y experiencias de discriminación utilizando los microdatos de la encuesta CASEN 2022. Se construyen índices sintéticos a partir de los módulos de redes (r7) y discriminación (r9), y se presentan análisis descriptivos y visualizaciones.

## Datos
- Fuente: Encuesta CASEN 2022 (microdatos).
- Unidad de análisis: Personas.
- Procesamiento: Recodificación de variables y construcción de índices aditivos.

## Metodología
- Selección de variables sociodemográficas (edad y sexo).
- Recodificación de r7 (apoyo) y r9 (discriminación).
- Construcción de índices sintéticos.
- Análisis descriptivo y gráficos por sexo.
- Enfoque reproducible con Quarto.

## Estructura
- `capstone_casen.qmd`: análisis reproducible.
- `data/processed/`: base procesada (.rds).
- `README.md`: descripción del proyecto.

## Resultados principales
- Apoyo social promedio moderado–alto.
- Discriminación promedio baja, pero concentrada en ciertos grupos.
- Diferencias por sexo más marcadas en la dispersión de la discriminación.

## Reproducibilidad
El análisis puede reproducirse ejecutando el archivo Quarto.
