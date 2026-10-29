# Explorador histórico de precipitación del Tena

[← Portafolio](../README.md)

**Python · NetCDF · Leaflet · Node-RED**  
**Estado:** Implementación documentada.

## Pregunta y contexto

Consultar espacial y temporalmente un archivo histórico de precipitación sin ejecutar entrenamiento o pronóstico.

## Enfoque técnico

Exportación de cuadros NetCDF a archivos diarios, conservación de valores y máscaras, manifiesto de procedencia y visualización cartográfica.

## Productos disponibles

Visor histórico, exportador y manifiesto de comprobación.

**Evidencia revisada:** tena-historico/README.md y componentes locales de exportación y consulta.

Referencia: [https://jaceconsultingec.com/geovisor/tena/](https://jaceconsultingec.com/geovisor/tena/). Disponibilidad web actual no verificada durante esta preparación.

## Alcance y limitaciones

Debe verificarse la correspondencia de las unidades con intensidad o acumulación antes de calcular totales. Las unidades regionales visualizadas no equivalen automáticamente al límite hidrológico validado del Tena.

## Desarrollo siguiente

Resolver unidades, validar el límite de cuenca y documentar versión del producto satelital antes de nuevos análisis hidrológicos.

## English

**Tena historical precipitation explorer**

Historical NetCDF archive explorer with provenance records. It does not run the predictive model; precipitation units and catchment boundaries require specific checks.

This entry documents existing work. Full code and datasets are not included in this portfolio. Availability of local files does not imply independent validation or permission to redistribute every source material.
