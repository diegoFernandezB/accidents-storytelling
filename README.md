# Predicción de Accidentes de Tránsito con Minería de Datos

Este proyecto corresponde al trabajo final del curso Minería de Datos, donde se aplicaron técnicas de análisis, modelado y visualización para predecir la cantidad de accidentes de tránsito bajo distintas condiciones urbanas, climáticas y viales.

## Objetivo

Demostrar cómo un modelo de regresión puede identificar factores de riesgo que aumentan la probabilidad de accidentes, transformando los resultados en una narrativa visual y comprensible.

## Modelo aplicado

Se utilizó un árbol de decisión (DecisionTreeRegressor) ajustado con GridSearchCV, trabajando sobre variables como:

- Densidad de tráfico
- Intensidad de lluvia
- Calidad del pavimento
- Multas de tránsito
- Velocidad promedio y otras

## Visualizaciones

Aquí algunas de las visualizaciones que sustentan nuestros insights:

### Variables más influyentes
![Wordcloud](img/nube.png)

### Relación pavimento y accidentes
![Scatter](img/grafi.png)

## Micrositio público (Storytelling)

Puedes ver el micrositio con todos los insights y visualizaciones en el siguiente enlace:  
https://TU_USUARIO.github.io/NOMBRE_DEL_REPO/

(Reemplazar con la URL real una vez activado GitHub Pages)

## Publicación en LinkedIn

(Agregar aquí el enlace a tu publicación en LinkedIn con resumen e insights)

## Estructura del repositorio

├── index.html # Micrositio principal
├── README.md # Descripción del proyecto
├── img/ # Carpeta de imágenes
│ ├── wordcloud.png
│ └── pavimento_vs_accidentes.png
├── modelos/ # Notebooks o scripts de modelos
│ └── accidentes_modelo.ipynb
└── data/ # Datos base usados (si corresponde)
