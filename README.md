# Análisis de la Eficiencia del Transporte: Caso Zuber Chicago 

## Descripción del Proyecto
Este proyecto analiza la base de datos de **Zuber**, una nueva empresa de viajes compartidos en Chicago. El objetivo principal es encontrar patrones en la información de los competidores y probar una hipótesis sobre el impacto de las condiciones climáticas en la duración de los viajes.

## Preguntas de Negocio
* ¿Cuál es la cuota de mercado de las principales empresas de taxis en Chicago?
* ¿Cuáles son los barrios donde más viajes finalizan?
* ¿Afecta el clima (lluvia) de manera significativa el tiempo de viaje desde el Loop hasta el Aeropuerto Internacional O'Hare?

## Tecnologías Utilizadas
* **SQL:** Extracción y modelado de datos de bases de datos relacionales.
* **Python:** Limpieza, procesamiento y análisis de datos.
* **Librerías:** Pandas, Matplotlib, Seaborn, Scipy (Estadística).
* **Estadística Inferencial:** Prueba T de Student para comparación de medias.

## Metodología y Hallazgos
1. **Análisis Exploratorio:** Se identificó que empresas como *Flash Cab* lideran el mercado, y que los barrios de *Loop* y *River North* concentran la mayor demanda.
2. **Prueba de Hipótesis:** - **H0:** La duración promedio de los viajes desde el Loop hasta el aeropuerto O'Hare no cambia los sábados lluviosos.
   - **H1:** La duración promedio de los viajes cambia los sábados lluviosos.
   - **Resultado:** Con un **p-value de 6.51e-12**, rechazamos la hipótesis nula, concluyendo que el clima tiene un impacto estadísticamente significativo en la operativa.

## Estructura del Repositorio
* `zuber_analysis.ipynb`: Notebook con el código completo, visualizaciones y conclusiones.
* `README.md`: Resumen ejecutivo del proyecto.

## Cómo visualizar el proyecto
Puedes ver el análisis completo directamente en el archivo `.ipynb` de este repositorio o clonarlo para ejecutarlo localmente.
