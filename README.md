# Práctica: Aprendizaje Automático - Predicción de Derrame Cerebral

## Descripción
Este proyecto forma parte de la asignatura de **Aprendizaje Automatico**. El objetivo es desarrollar modelos de clasificación para predecir la probabilidad de que un paciente sufra un accidente cerebrovascular (stroke) basándose en parámetros clínicos y demográficos.

## Contenido del análisis
El trabajo se estructura en dos grandes bloques:

1.  **Análisis Exploratorio y Preprocesamiento:**
    *   Tratamiento de valores faltantes (imputación de `bmi`).
    *   Análisis de la distribución de variables y su relación con la variable objetivo.
    *   Identificación del fuerte desequilibrio de clases (clase positiva < 5%).
    *   Reducción de dimensionalidad mediante **PCA**.

2.  **Modelado y Evaluación:**
    *   **Aprendizaje no supervisado:** Clustering (K-means y jerárquico) para identificar patrones en pacientes.
    *   **Aprendizaje supervisado:**
        *   Regresión Logística.
        *   Análisis Discriminante Lineal (LDA).
        *   K-Vecinos (KNN).
        *   Árboles de Decisión (con técnicas de balanceo de clases).
        *   AdaBoost.
        *   Random Forest (comparativa entre modelo original y balanceado mediante ROSE).
