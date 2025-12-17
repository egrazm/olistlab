# OlistLab

Proyecto de ciencia de datos usando el dataset de Olist.

Objetivo:
- Practicar y documentar modelos de clasificación, regresión y clustering con scikit-learn.
- Resolver al menos 3 casos: deserción de clientes, recomendación de productos y estimación de tiempos de entrega.

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

Notebook:
- `01_exploracion.ipynb`

---

### 🔹 Día 2 — Predicción de Deserción (Churn)
- Definición de la variable objetivo *churn*
- Cálculo de la última compra por cliente
- Creación de la métrica `days_since_last_purchase`
- Feature engineering inicial (frecuencia, gasto, reseñas)
- Preprocesamiento de datos para Machine Learning

Notebook:
- `02_churn_preprocessing.ipynb`

---

## 🚧 Próximos Pasos

- Entrenamiento y comparación de modelos de clasificación para churn
- Implementación del sistema de recomendación mediante clustering
- Predicción de tiempos de entrega con modelos de regresión
- Análisis y conclusiones finales

---

## 📌 Notas Finales

Este proyecto se desarrolla de forma incremental, con commits claros que documentan cada avance, simulando un flujo de trabajo real en ciencia de datos.