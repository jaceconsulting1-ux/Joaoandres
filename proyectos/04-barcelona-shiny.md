# Visor hidrometeorológico Barcelona–Valdivia

[← Portafolio](../README.md)

**R · Shiny · Plotly · bslib**  
**Estado:** Aplicación local; alojamiento público por confirmar.

## Pregunta y contexto

Explorar precipitación, eventos de lluvia, temperatura, humedad y viento mediante una interfaz interactiva.

## Enfoque técnico

Lectura de un objeto R externo, filtros temporales, gráficos interactivos y separación entre aplicación y datos mediante variable de entorno.

## Productos disponibles

Aplicación Shiny con secciones temáticas y documentación de ejecución y esquema de datos.

**Evidencia revisada:** estacion-meteorologica/app.R y README de ejecución.

## Alcance y limitaciones

Necesita un servidor R/Shiny. Los datos representados llegan al navegador aunque no haya descarga tabular. Incorporar el código no prueba por sí solo la validez de imputaciones o clasificación de eventos.

## Desarrollo siguiente

Preparar datos demostrativos identificados como sintéticos y un entorno reproducible. Confirmar datos autorizados antes del despliegue público.

## English

**Barcelona–Valdivia Shiny dashboard**

Shiny and Plotly application for station observations and rainfall events. Source data are supplied separately; a running public deployment is not claimed.

This entry documents existing work. Full code and datasets are not included in this portfolio. Availability of local files does not imply independent validation or permission to redistribute every source material.
