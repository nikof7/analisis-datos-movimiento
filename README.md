# Análisis de movimiento de perros en distintos ambientes

Este repositorio contiene un análisis exploratorio del movimiento de perros con GPS, con foco en cómo variables como la velocidad, la distancia recorrida, la sinuosidad de la trayectoria y el cambio de dirección varían según el tipo de ambiente donde se mueven.

## Archivos incluidos

* **`analisis-movimiento.Rmd`**
  Documento en R Markdown que contiene todo el análisis y visualizaciones paso a paso.

* **`analisis-movimiento.html`**
  Versión renderizada del análisis, que se puede abrir en cualquier navegador para una visualización completa del informe.

* **`trayectoria_animada.gif`**
  Animación que muestra la trayectoria de un perro a lo largo del tiempo con flechas que indican dirección de movimiento y cambio de dirección entre pasos.

## Contenido del análisis

* Visualización de trayectorias GPS con `leaflet` y `ggplot2`.
* Cálculo de métricas de movimiento: velocidad, distancia, dirección, cambio de ángulo.
* Comparaciones de movimiento entre distintos usos del suelo.
* Exploración visual y animada del comportamiento espacial.
