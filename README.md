# 📊 Análisis de Evasión de Clientes (Churn) - TelecomX LATAM

## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar la evasión de clientes (*Churn*) en la empresa TelecomX LATAM a partir de datos obtenidos desde una API en formato JSON.

El análisis incluye el proceso completo de:

- Extracción de datos desde API
- Limpieza y tratamiento de datos
- Análisis Exploratorio de Datos (EDA)
- Visualización de patrones relevantes
- Generación de conclusiones e insights estratégicos

El propósito principal es identificar factores asociados a la cancelación del servicio y proponer recomendaciones que ayuden a reducir la evasión de clientes.

---

## 🎯 Objetivos del Análisis

- Comprender la estructura del dataset.
- Detectar inconsistencias y valores faltantes.
- Analizar la distribución de la variable **Churn**.
- Explorar la relación entre la evasión y variables categóricas (contrato, método de pago, servicios).
- Analizar variables numéricas como tiempo de permanencia y cargos mensuales.
- Generar recomendaciones basadas en datos.

---

## 🛠️ Tecnologías Utilizadas

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 🔎 Proceso Realizado

### 1️⃣ Extracción de Datos

Los datos fueron importados desde una API en formato JSON y posteriormente transformados en un DataFrame utilizando la librería **pandas**, lo que permitió su manipulación y análisis estructurado.

---

### 2️⃣ Limpieza y Tratamiento

Durante esta etapa se realizaron las siguientes tareas:

- Normalización de estructuras anidadas provenientes del JSON.
- Conversión de tipos de datos para asegurar coherencia en el análisis.
- Identificación y tratamiento de valores nulos.
- Eliminación de registros inconsistentes o incompletos.
- Creación de la variable **Cuentas_Diarias**, calculada a partir de los cargos mensuales.

---

### 3️⃣ Análisis Exploratorio de Datos (EDA)

Se llevaron a cabo distintos análisis para comprender el comportamiento de los clientes:

- Cálculo de estadísticas descriptivas.
- Análisis de la distribución de la variable **Churn**.
- Comparación de la evasión según tipo de contrato.
- Análisis del tiempo de permanencia y cargos mensuales.
- Visualizaciones para identificar patrones y tendencias relevantes.

---

### 4️⃣ Conclusiones e Insights

A partir del análisis se identificaron patrones como:

- Mayor evasión en clientes con contratos mensuales.
- Mayor cancelación en clientes con menor tiempo de permanencia.
- Asociación entre cargos mensuales y probabilidad de churn.

---

### 5️⃣ Recomendaciones

En base a los hallazgos, se proponen las siguientes acciones:

- Implementar estrategias de fidelización temprana.
- Diseñar acciones específicas para clientes con contratos mensuales.
- Desarrollar medidas preventivas durante los primeros meses del servicio.
