# Machine Learning hidrológico en el río Tena

[← Portafolio](../README.md)

**R · Random Forest · hidrometeorología**  
**Estado:** Repositorio público; revisión metodológica pendiente.

## Pregunta y contexto

Investigar relaciones entre lluvia, caudal y eventos de crecida en el río Tena, Ecuador.

## Enfoque técnico

Modelos de regresión y clasificación, análisis de retardos y variables hidrometeorológicas; revisión diagnóstica de predictores y definición de la respuesta.

## Productos disponibles

Repositorio Dynamics_prediction_model y scripts locales de diagnóstico metodológico.

**Evidencia revisada:** Repositorio público y ejecutar_diagnostico.R / ejecutar_caudal_diagnostico.R.

Referencia: [https://github.com/Joaoandres/Dynamics_prediction_model](https://github.com/Joaoandres/Dynamics_prediction_model). Disponibilidad web actual no verificada durante esta preparación.

## Alcance y limitaciones

Los diagnósticos locales documentan fuga de información: antec incluye descarga contemporánea y Qr.peak interviene en la definición de la clase y como predictor. Las métricas históricas del README original no se usan aquí como evidencia de capacidad de pronóstico.

## Desarrollo siguiente

Definir horizonte de anticipación, reconstruir predictores disponibles al emitir cada pronóstico, separar cronológicamente entrenamiento/ajuste/prueba y evaluar eventos independientes frente a persistencia y otros modelos de referencia.

## English

**Hydrological Machine Learning in the Tena River**

Random Forest research on rainfall–discharge dynamics. Local diagnostic scripts identify target leakage; historical performance scores do not establish operational forecast skill.

This entry documents existing work. Full code and datasets are not included in this portfolio. Availability of local files does not imply independent validation or permission to redistribute every source material.
