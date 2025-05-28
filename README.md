# 🛍️ Segmentación de Clientes con Clustering y Análisis de Churn

Este proyecto utiliza técnicas de análisis exploratorio de datos (EDA) y machine learning no supervisado para segmentar a los clientes de un e-commerce. Se analizan características demográficas y de comportamiento para identificar perfiles clave y detectar patrones de abandono (churn).

---

## 🎯 Objetivo

- Aplicar análisis exploratorio y limpieza de datos para comprender el comportamiento de los clientes.
- Usar **K-Means clustering** para segmentar en grupos con patrones similares.
- Calcular la **tasa de churn** por cluster e identificar perfiles de riesgo.
- Construir un **dashboard en Power BI** que facilite la toma de decisiones para marketing y retención.

---

## 📊 Dataset

El dataset contiene información de clientes de un e-commerce ficticio, con las siguientes columnas:

- `CustomerID`
- `Age`
- `Gender`
- `Annual_Income_USD`
- `Spending_Score`
- `Country`
- `Churned` (0 = No, 1 = Sí)

---

## 🧹 Limpieza de datos

- Eliminación de outliers con IQR.
- Imputación de valores nulos:
  - Mediana para edad y score.
  - Moda para género.
- Conversión de variables categóricas y creación de clusters.

---

## 🔍 Análisis Exploratorio

- Distribución de edad, ingresos y score.
- Comparación de medias según churn.
- T-Test para validar diferencias significativas entre grupos.

---

## 🤖 Clustering (K-Means)

- Se aplicó **KMeans** con 3 clusters (determinados por el método del codo).
- Se estandarizaron las variables para evitar sesgos por escala.
- Se interpretó cada grupo según edad, ingreso, gasto y tasa de abandono.

---

## 📈 Visualizaciones

- Scatterplot: `Annual Income` vs `Spending Score` por cluster.
- Gráficos de barras horizontales: tasa de churn por cluster.
- Tabla: perfil promedio por cluster.
- KPI Cards: edad promedio, ingreso, score y churn general.
- Dashboard en Power BI con layout optimizado.

---

## 📌 Principales Insights

- Clientes con **menor ingreso gastan más y abandonan menos**.
- Clientes con **mayor ingreso tienden a gastar menos y abandonan más**.
- El **cluster 2 es el más riesgoso** y necesita campañas de retención personalizadas.
- El **cluster 1 es el más rentable** a pesar de ser de ingresos bajos.

---

## 💼 Herramientas Utilizadas

- Python (pandas, seaborn, sklearn)
- Jupyter Notebook
- Power BI
- Git & GitHub

---

## 🧑‍💻 Autor

**Miguel A. Castillo S.**  
Análisis de Datos | Segmentación de Clientes | Power BI  
📅 Mayo 2025

---
