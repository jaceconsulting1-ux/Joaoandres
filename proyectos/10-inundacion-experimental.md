# Prototipo de simulación de inundación sobre DEM

[← Portafolio](../README.md)

**Python · NumPy · SciPy · GDAL**  
**Estado:** Prototipo experimental.

## Pregunta y contexto

Explorar la propagación superficial de agua sobre un DEM y comprobar propiedades numéricas básicas.

## Enfoque técnico

Esquema ráster bidimensional de aproximación inercial local, separación entre diagnóstico de drenaje y terreno hidráulico, controles de grilla proyectada y unidades SI.

## Productos disponibles

Código de preparación y simulación, interfaz de servicio y pruebas en el código para dominio seco, lago en reposo, conservación de masa y positividad.

**Evidencia revisada:** flood.py y tests/test_physics.py. No se ejecutaron estas pruebas al preparar el portafolio.

## Alcance y limitaciones

No incorpora momento advectivo, mareas, alcantarillas, drenaje urbano ni batimetría fluvial. Las pruebas no demuestran calibración con inundaciones observadas. No se presenta como sistema de alerta.

## Desarrollo siguiente

Documentar contornos, estabilidad temporal, fricción y balance de volumen; contrastar con soluciones de referencia y observaciones independientes.

## English

**Experimental DEM-based flood routing**

Experimental local-inertial raster solver with physical-property tests in source. No observed flood validation or operational readiness is claimed.

This entry documents existing work. Full code and datasets are not included in this portfolio. Availability of local files does not imply independent validation or permission to redistribute every source material.
