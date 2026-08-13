# Regresión, clasificación y clustering: viviendas y vinos

Trabajo de la materia **Laboratorio de Datos** (FCEyN, UBA, 2025), realizado en conjunto con [Maximiliano Rodríguez Camps](https://github.com/).

Este trabajo combina dos ejercicios que juntos cubren las tres tareas centrales del aprendizaje automático: regresión, clasificación y clustering.

## Parte 1: Precios de viviendas en Argentina

- **Curaduría de datos**: limpieza de un dataset con errores de encoding y provincias mal escritas.
- **Regresión lineal**: predicción del precio de la propiedad en USD (R² = 0.42).
- **Regresión logística (clasificación)**: predicción de si una propiedad está ubicada en CABA/AMBA o no, evaluada con matriz de confusión.

## Parte 2: Vinos (tinto/blanco)

- **PCA (Análisis de Componentes Principales)**: reducción de dimensionalidad del dataset de propiedades fisicoquímicas del vino.
- **K-Means (clustering no supervisado)**: agrupamiento de los vinos sin usar la etiqueta tinto/blanco, eligiendo el número de clusters mediante el método del codo (inertia) y el coeficiente de silhouette.
- **Interpretación**: evaluación de qué tan bien los clusters encontrados se correspondían con la distinción real tinto/blanco, que el modelo no vio durante el entrenamiento.

## Por qué este trabajo en particular

A diferencia de un ejercicio enfocado en una sola técnica, este trabajo recorre las tres grandes familias del aprendizaje automático (regresión, clasificación, clustering) sobre datos reales, incluyendo la selección de métricas apropiadas para cada tipo de problema.

## Herramientas

Python · scikit-learn (LinearRegression, LogisticRegression, PCA, KMeans) · pandas · matplotlib
