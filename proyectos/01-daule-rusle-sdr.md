# Erosión y transferencia de sedimentos en el Daule

[← Portafolio](../README.md)

**R · Python · SIG · RUSLE · InVEST SDR**  
**Estado:** Investigación y flujo documentados.

## Pregunta y contexto

Identificar la distribución espacial de la erosión hídrica potencial y de la transferencia potencial hacia la red de drenaje de la cuenca del río Daule, Ecuador.

## Enfoque técnico

Integración de R, K, LS, C y P; cálculo de A = R × K × LS × C × P; acoplamiento con SDR; comparación de escenarios de erosividad y contraste con observaciones de campo y UAV.

## Productos disponibles

Factores y resultados ráster, tablas, scripts modulares y un paquete local de reproducibilidad con entorno definido y manifiesto SHA-256.

**Evidencia revisada:** Flujo modular RUSLE y paquete local daule_rusle_sdr_reproducibility.

## Alcance y limitaciones

RUSLE estima erosión potencial laminar y en surcos. A × SDR representa transferencia potencial según el modelo. El contraste con índices de campo no equivale a calibración en toneladas. El paquete reproduce cálculos desde insumos preparados; su producción completa desde fuentes originales queda fuera de esa frontera.

## Desarrollo siguiente

Preparar un repositorio de métodos con rutas relativas, atribuciones y un ejemplo pequeño autorizado. Este portafolio no redistribuye los insumos.

## English

**Daule soil erosion and sediment delivery**

Spatial RUSLE–SDR workflow with reproducibility documentation and field/UAV comparisons. Potential estimates are distinct from measured soil loss or sediment loads.

This entry documents existing work. Full code and datasets are not included in this portfolio. Availability of local files does not imply independent validation or permission to redistribute every source material.
