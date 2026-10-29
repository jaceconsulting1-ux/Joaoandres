# Control de calidad de series Barcelona–Valdivia

[← Portafolio](../README.md)

**R · data.table · series temporales · auditoría**  
**Estado:** Pipeline y verificaciones locales disponibles.

## Pregunta y contexto

Homogeneizar registros de estación, detectar inconsistencias y gestionar huecos sin perder la trazabilidad de las observaciones.

## Enfoque técnico

Normalización de formatos y zona horaria America/Guayaquil, alineación a cinco minutos, controles físicos y estados por variable. Lluvia: ceros solo en huecos internos de hasta 15 minutos delimitados por ceros. Variables meteorológicas elegibles: interpolación interna de hasta 30 minutos; dirección del viento tratada circularmente.

## Productos disponibles

Archivos normalizados, auditorías, serie con estados observado/imputado/pendiente y comprobaciones con bloques ocultos.

**Evidencia revisada:** Scripts revisados 001–003, pipeline_comun.R y verificaciones de la revisión 001–013.

## Alcance y limitaciones

La humedad de suelo no se imputa. Los huecos delimitados por lluvia cero pueden ocultar eventos; el código evalúa ese riesgo. La interpolación no sustituye observaciones y requiere revisión según estación e instrumento.

## Desarrollo siguiente

Extraer el pipeline con configuración portable y datos sintéticos o autorizados, conservando las banderas de calidad.

## English

**Barcelona–Valdivia time-series quality control**

Auditable five-minute station processing with variable-specific gap handling, physical checks and quality flags. Soil moisture remains unimputed.

This entry documents existing work. Full code and datasets are not included in this portfolio. Availability of local files does not imply independent validation or permission to redistribute every source material.
