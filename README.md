# Análisis de datos mediante técnicas de Machine Learning

![Machine Learning](https://img.shields.io/badge/tema-Machine%20Learning-blue)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Universidad Nacional de Colombia](https://img.shields.io/badge/Universidad-Nacional%20de%20Colombia-green)

## Descripción

Este repositorio contiene la **monografía "Análisis de datos mediante técnicas de Machine Learning"**, desarrollada como trabajo académico para optar al título de **Ingeniero Electrónico** en la Universidad Nacional de Colombia.

El trabajo estudia la importancia de los datos como base de los sistemas de aprendizaje automático y presenta fundamentos teóricos y aplicaciones computacionales de técnicas de **Machine Learning supervisado y no supervisado**.

## Autor

**Jholman Dasney Meza Pasinga**  
Ingeniería Electrónica  
Universidad Nacional de Colombia

**Tutor:** Jorge Hernan Estrada Estrada

**Manizales, Colombia — 2026**

## Contenido

La monografía aborda, entre otros, los siguientes temas:

- Datos como materia prima para los sistemas inteligentes.
- Tipos de datos, variables, características y etiquetas.
- Preparación y calidad de los datos.
- Fundamentos de Machine Learning.
- Aprendizaje supervisado y no supervisado.
- Modelos de regresión y clasificación.
- Regresión lineal.
- Regresión logística.
- Métricas de evaluación de modelos.
- Agrupamiento mediante **K-Means**.
- Reducción de dimensionalidad mediante **PCA (Análisis de Componentes Principales)**.
- Visualización y análisis de resultados.
- Calidad de los datos, privacidad y seguridad de la información.
- Costos computacionales.
- Retos y tendencias futuras del aprendizaje automático.

## Aplicaciones desarrolladas

### 1. Regresión lineal — California Housing

Se implementa un modelo de regresión lineal para estudiar la capacidad de predecir el valor medio de las viviendas a partir del ingreso medio de una zona geográfica, utilizando el conjunto de datos **California Housing** disponible mediante `scikit-learn`.

Entre las métricas analizadas se encuentran:

- Coeficiente de determinación (R²).
- RMSE (Root Mean Squared Error).

### 2. Clasificación — Aprendizaje supervisado

Se estudian modelos de clasificación y sus correspondientes métricas de evaluación, incluyendo elementos como:

- Distribución de clases.
- Matriz de correlación.
- Matriz de confusión.
- Accuracy.
- Precision.
- Recall.
- F1-score.
- ROC-AUC.

### 3. K-Means — Dataset Iris

Se implementa el algoritmo **K-Means** sobre el conjunto de datos Iris para identificar agrupamientos sin utilizar las etiquetas durante el entrenamiento.

El análisis incluye:

- Distribución de los datos.
- Selección del número de clústeres mediante el método del codo.
- Agrupamientos encontrados.
- Inercia.
- Coeficiente de silueta.

### 4. PCA — Dataset Wine

Se aplica **PCA** al conjunto de datos Wine para reducir sus 13 dimensiones originales y facilitar la visualización e interpretación de la estructura de los datos.

Se analiza:

- Varianza explicada.
- Varianza acumulada.
- Proyección de los datos.
- Contribución de las variables originales.
- Componentes principales.

## Tecnologías y herramientas

El trabajo utiliza principalmente:

- **Python**
- **scikit-learn**
- Análisis y visualización de datos
- Técnicas de Machine Learning
- Métodos estadísticos y métricas de evaluación

## Principales conclusiones

El trabajo destaca que la calidad, preparación y representatividad de los datos son fundamentales para obtener resultados confiables en Machine Learning.

También se concluye que los modelos de aprendizaje automático son herramientas para apoyar el análisis y la toma de decisiones, pero no deben considerarse sustitutos absolutos del criterio humano. La selección del modelo debe considerar el problema, la precisión, la interpretabilidad, los recursos disponibles y el propósito del análisis.

## Documento

El documento completo se encuentra en:

**[Monografia_Jholman_Meza.pdf](./Monografia_Jholman_Meza.pdf)**

## Repositorio

Este repositorio se presenta como parte del portafolio académico y profesional del autor, con el propósito de documentar el trabajo realizado sobre análisis de datos y aprendizaje automático.

## Licencia

Documento académico. Todos los derechos corresponden a su autor, salvo las fuentes, datasets y referencias externas citadas dentro de la monografía.
