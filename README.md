# Telecomx_parte_2
# 📊 TelecomX - Análisis de Cancelación de Clientes (Churn)

Análisis de cancelación de clientes (Churn) en una empresa de telecomunicaciones utilizando **Python, análisis exploratorio de datos y modelos de machine learning**.

---

## 📌 Descripción

Este proyecto analiza la **cancelación de clientes (Churn)** en una empresa de telecomunicaciones con el objetivo de identificar los factores que influyen en la pérdida de clientes.

A través de **análisis exploratorio de datos (EDA)** y **modelos de machine learning**, se busca encontrar patrones que permitan predecir qué clientes tienen mayor probabilidad de cancelar el servicio.

Este tipo de análisis permite a las empresas implementar **estrategias de retención más efectivas**.

---

## 🛠 Tecnologías utilizadas

* 🐍 Python
* 📊 Pandas
* 📉 NumPy
* 📈 Matplotlib
* 🎨 Seaborn
* 🤖 Scikit-learn
* 📓 Google Colab / Jupyter Notebook

---

## 🔍 Análisis realizado

El proyecto incluye las siguientes etapas de análisis de datos:

* Extracción y carga de datos
* Limpieza y preparación de datos
* Eliminación de variables irrelevantes
* Transformación de variables categóricas (One-Hot Encoding)
* Análisis exploratorio de datos (EDA)
* Matriz de correlación entre variables
* Visualización de patrones relacionados con la cancelación

---

## 🤖 Modelos de Machine Learning

Se implementaron dos modelos para predecir la cancelación de clientes:

**1️⃣ Regresión Logística**

* Modelo sensible a la escala de los datos
* Se aplicó normalización utilizando `StandardScaler`

**2️⃣ Random Forest**

* Modelo basado en árboles de decisión
* No requiere normalización de los datos

---

## 📊 Evaluación de los Modelos

Los modelos fueron evaluados utilizando métricas de clasificación:

* Exactitud (Accuracy)
* Precisión (Precision)
* Recall
* F1-score
* Matriz de confusión

Esto permitió comparar el rendimiento de ambos modelos y analizar su capacidad para predecir la cancelación de clientes.

---

## 📈 Principales hallazgos

A partir del análisis realizado se identificaron algunos factores importantes relacionados con la cancelación:

* Los clientes con **mayores cargos mensuales** presentan mayor probabilidad de cancelar.
* Los clientes con **menor tiempo de permanencia (tenure)** tienen mayor churn.
* Algunas características del servicio contratado influyen en la permanencia del cliente.

---

## 🚀 Recomendaciones

Basado en los resultados obtenidos, se sugieren algunas estrategias para reducir la cancelación:

* Incentivar **contratos de mayor duración**.
* Implementar **programas de fidelización para clientes nuevos**.
* Identificar clientes con **alto riesgo de cancelación** mediante modelos predictivos.
* Ofrecer promociones o beneficios personalizados para mejorar la retención.

---

## 📂 Estructura del Proyecto

```
TelecomX-Churn-Analysis
│
├── Telecom_x_Parte_2.ipynb
├── TelecomX_tratado.csv
└── README.md
```

Proyecto de análisis de datos enfocado en **predicción de cancelación de clientes (Customer Churn)** utilizando técnicas de **Data Analysis y Machine Learning**.

