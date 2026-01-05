# OlistLab 📦📊

Proyecto de **Ciencia de Datos aplicada** utilizando el dataset público de **Olist** (e-commerce brasileño).

El objetivo es simular un entorno real de trabajo en Data Science, abordando problemas de negocio concretos mediante **aprendizaje supervisado y no supervisado**, utilizando **scikit-learn** y buenas prácticas de experimentación, validación e interpretación de resultados.

---

## 🎯 Objetivos del Proyecto

- Aplicar modelos de **clasificación, regresión y clustering** con scikit-learn.
- Resolver **al menos 3 casos de negocio reales**:
  - Predicción de deserción de clientes (churn)
  - Recomendación de productos
  - Estimación de tiempos de entrega
- Comparar múltiples modelos por problema y justificar la selección final.
- Generar visualizaciones e insights accionables.
- Documentar todo el proceso de forma clara y reproducible.

---

## 🧠 Casos de Uso Implementados

### 1️⃣ Predicción de Deserción de Clientes (Churn)
**Objetivo:** Identificar clientes con riesgo de abandonar la plataforma.

- Definición de variable objetivo `churn`
- Feature engineering:
  - Días desde la última compra
  - Frecuencia de compra
  - Gasto total
  - Puntajes de reseñas
- Modelos evaluados:
  - Regresión Logística
  - Árbol de Decisión
  - Random Forest
  - Gradient Boosting
  - SVM
  - k-NN
  - Naive Bayes
- Evaluación con métricas de clasificación y control de overfitting

---

### 2️⃣ Recomendación de Productos (Clustering)
**Objetivo:** Agrupar productos para sugerencias personalizadas.

- Uso de atributos como:
  - Categoría
  - Precio
  - Puntajes de reseñas
- Reducción de dimensionalidad con **PCA**
- Clustering con **k-Means**
- Análisis e interpretación de clusters obtenidos

---

### 3️⃣ Estimación de Tiempos de Entrega
**Objetivo:** Predecir la duración de entrega de pedidos y detectar riesgos de retraso.

- Variables consideradas:
  - Ubicación del cliente
  - Categoría del producto
  - Historial de entregas
- Modelos evaluados:
  - Regresión Lineal
  - Árbol de Decisión
  - Random Forest
  - Gradient Boosting
- Evaluación mediante métricas de regresión (MAE, RMSE)

---

## 🧪 Bitácora de Desarrollo

### 🔹 Día 0 — Inicialización del Proyecto
- Creación del repositorio `OlistLab`
- Configuración de Git y GitHub
- Definición de la estructura del proyecto
- Configuración de `.gitignore` y `requirements.txt`

---

### 🔹 Día 1 — Exploración y Análisis Inicial (EDA)
- Carga de los datasets principales de Olist
- Análisis exploratorio de pedidos, clientes y productos
- Identificación de valores nulos y tipos de datos
- Visualización de distribuciones y patrones iniciales

📓 Notebook:
- `01_exploracion.ipynb`

---

### 🔹 Día 2 — Predicción de Deserción (Preprocesamiento)
- Definición de la variable objetivo `churn`
- Cálculo de la última compra por cliente
- Creación de la métrica `days_since_last_purchase`
- Feature engineering inicial
- Preprocesamiento de datos para modelos de Machine Learning

📓 Notebook:
- `02_churn_preprocessing.ipynb`

---

### 🔹 Próximos Pasos
- Entrenamiento y comparación de modelos de clasificación para churn
- Implementación completa del sistema de recomendación mediante clustering
- Entrenamiento y evaluación de modelos de regresión para tiempos de entrega
- Análisis comparativo y conclusiones finales

---

## 🛠️ Tecnologías Utilizadas

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- Jupyter Notebook
- Git & GitHub

---

## 📌 Notas Finales

Este proyecto se desarrolla de forma incremental, con **commits claros y documentados**, simulando un flujo de trabajo real en ciencia de datos.

Se prioriza:
- Correcta validación de modelos
- Interpretación de resultados
- Control de overfitting
- Reproducibilidad del análisis

---

📎 Dataset: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce