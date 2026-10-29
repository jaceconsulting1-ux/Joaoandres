# Automatización de boletines meteorológicos regionales

[← Portafolio](../README.md)

**Python · GRIB · ecCodes · estadística zonal · H3**  
**Estado:** Código y documentación disponibles.

## Pregunta y contexto

Transformar salidas meteorológicas en mapas y resúmenes regionales trazables de precipitación y temperatura.

## Enfoque técnico

Procesamiento GRIB, control del error de empaquetado e incrementos acumulados, intersección de celdas con provincias y ponderación por superficie en un sistema equivalente; visualización temporal y contenido bilingüe.

## Productos disponibles

Mapas, animaciones, tablas provinciales, metadatos y pruebas de agregación y empaquetado.

**Evidencia revisada:** tools/weather/README.md y módulos de procesamiento, publicación y pruebas.

## Alcance y limitaciones

Una corrida determinista no proporciona probabilidades de evento. La fracción de superficie con lluvia no es probabilidad. El error de empaquetado no representa incertidumbre meteorológica y H3 no mejora la resolución fuente.

## Desarrollo siguiente

Separar procesamiento y publicación, documentar fuentes y condiciones de uso y preparar una corrida histórica pequeña como demostración.

## English

**Automated regional weather bulletins**

GRIB-to-bulletin pipeline with area-weighted provincial summaries and packing-error checks. Deterministic spatial coverage is not an event probability.

This entry documents existing work. Full code and datasets are not included in this portfolio. Availability of local files does not imply independent validation or permission to redistribute every source material.
