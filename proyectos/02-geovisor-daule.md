# Geovisor y escenarios de conservación del suelo

[← Portafolio](../README.md)

**JavaScript · H3 · cartografía web · Python**  
**Estado:** Implementación documentada.

## Pregunta y contexto

Facilitar la exploración de factores de erosión, coberturas y escenarios de manejo para usuarios técnicos.

## Enfoque técnico

Visualización H3, agregación ponderada de resultados de la malla nativa, controles de P por uso del suelo, sensibilidad del SDR y metadatos de procedencia.

## Productos disponibles

Interfaz interactiva, capas temáticas, controles de escenarios y metadatos de resolución, agregación y fuentes.

**Evidencia revisada:** Código del geovisor y metadatos publication.json.

Referencia: [https://jaceconsultingec.com/geovisor/](https://jaceconsultingec.com/geovisor/). Disponibilidad web actual no verificada durante esta preparación.

## Alcance y limitaciones

La agregación cartográfica suaviza extremos y no aporta nueva resolución espacial. Modificar el multiplicador SDR es sensibilidad, no una nueva ejecución de InVEST ni recalibración.

## Desarrollo siguiente

Separar interfaz y datos autorizados y documentar las escalas de análisis y visualización.

## English

**Daule geospatial scenario explorer**

Interactive H3 explorer for erosion factors and land-management scenarios. Scenario controls are sensitivity experiments; cartographic aggregation does not increase source resolution.

This entry documents existing work. Full code and datasets are not included in this portfolio. Availability of local files does not imply independent validation or permission to redistribute every source material.
