## 📌 Descripción del proyecto


Trabajas en la compañía de extracción de petróleo OilyGiant. Tu tarea es encontrar los mejores lugares donde abrir 200 pozos nuevos de petróleo.

Las tareas principales realizadas fueron:

- Cargar los archivos con los parámetros recogidos de pozos petrolíferos en tres regiones: calidad de crudo y volumen de reservas.

- Creación un modelo para predecir el volumen de reservas en pozos nuevos.

- Elegir los pozos petrolíferos que tienen los valores estimados más altos.

- Elegir la región con el beneficio total más alto para los pozos petrolíferos seleccionados.

- Creación de un modelo que ayude a elegir la región con el mayor margen de beneficio. 

- Analizamos los beneficios y riesgos potenciales utilizando la técnica bootstrapping.


## 🔍 Hallazgos clave


Tras el análisis comparativo de las tres regiones mediante modelos predictivos y simulaciones de riesgo (bootstrap con 1000 iteraciones), se determinaron los beneficios esperados y la probabilidad de pérdidas para la apertura de 200 nuevos pozos petrolíferos.

Región 0: beneficio promedio estimado de ≈33 millones USD, con un intervalo de confianza al 95% entre 30 y 36 millones USD y probabilidad de pérdida 0%.

Región 1: beneficio promedio de ≈24 millones USD, sin variabilidad en las simulaciones (intervalo estrecho), pero con un margen de ganancia menor frente a la Región 0.

Región 2: beneficio promedio de ≈27 millones USD, con mayor dispersión (IC 95% entre 23 y 30 millones USD), aunque igualmente sin riesgo de pérdidas.




--- 

## 🧑‍🎓 Lo que hice como estudiante

- Realizé una carga y exploración de datos exhaustiva.

- Creé funciones reutilizables que mejoran la modularidad del código.

- Implementé modelos de regresión y evalué su rendimiento.

- Definí parámetros de negocio de manera clara y estructurada.

- Calculé ganancias estimadas de manera efectiva para cada región.

- Implementé un análisis de riesgo robusto utilizando bootstrap.

- Utilizé métricas de RMSE y niveles de confianza para evaluar el rendimiento del modelo.

- Proporcioé visualizaciones útiles para entender la distribución de datos.
