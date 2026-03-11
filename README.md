# 📊 TelecomX - Predicción de Cancelación de Clientes (Churn)

## 📖 Descripción del proyecto

Este proyecto tiene como objetivo desarrollar un modelo predictivo capaz de estimar la probabilidad de cancelación de clientes (churn) en la empresa ficticia **TelecomX**.

La cancelación de clientes representa uno de los principales desafíos para empresas de telecomunicaciones, ya que implica una pérdida directa de ingresos y mayores costos de adquisición de nuevos clientes. A través del uso de técnicas de análisis de datos y machine learning, es posible identificar patrones en el comportamiento de los clientes que permitan anticipar el riesgo de cancelación.

En este proyecto se utilizó el conjunto de datos previamente preparado en la etapa de **ETL**, donde se limpiaron, transformaron y estructuraron los datos de clientes provenientes de una API.

A partir de este dataset se realizó un análisis exploratorio, un estudio de correlaciones entre variables y la construcción de un modelo de **regresión logística** para predecir el churn.

---

## 🎯 Objetivos del proyecto

* Analizar el comportamiento de los clientes de TelecomX.
* Identificar factores asociados a la cancelación del servicio.
* Preparar los datos para la construcción de modelos predictivos.
* Implementar un modelo de machine learning para estimar el riesgo de churn.
* Evaluar el desempeño del modelo mediante métricas de clasificación.

---

## 🧰 Tecnologías utilizadas

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Jupyter Notebook / Google Colab**

---

## 📂 Fuente de datos

Los datos utilizados en este proyecto provienen del dataset de clientes de **TelecomX**, el cual contiene información sobre:

* características demográficas de los clientes
* servicios contratados
* tipo de contrato
* método de pago
* cargos mensuales y totales
* estado de cancelación del servicio (Churn)

El dataset fue previamente preparado mediante un proceso de **ETL**, donde se realizaron tareas de limpieza, normalización y transformación de datos.

---

## 🔎 Proceso de análisis

El desarrollo del proyecto siguió las siguientes etapas:

### 1️⃣ Exploración de datos (EDA)

Se realizó un análisis exploratorio para comprender la distribución de las variables y observar patrones relacionados con la cancelación de clientes.

Se analizaron variables como:

* tipo de contrato
* servicio de internet
* cargos mensuales
* duración del cliente en la empresa

Además, se generaron visualizaciones para identificar posibles relaciones entre estas variables y el churn.

---

### 2️⃣ Preparación de datos

Para poder aplicar modelos de machine learning, fue necesario transformar las variables categóricas mediante **One-Hot Encoding** y convertir la variable objetivo (Churn) en una variable binaria.

También se realizó la división del dataset en conjuntos de **entrenamiento y prueba**, permitiendo evaluar el modelo de forma más confiable.

---

### 3️⃣ Construcción del modelo predictivo

Se utilizó un modelo de **Regresión Logística**, una técnica ampliamente utilizada para problemas de clasificación binaria.

El modelo fue entrenado utilizando el conjunto de entrenamiento y posteriormente evaluado con el conjunto de prueba.

---

### 4️⃣ Evaluación del modelo

El desempeño del modelo fue evaluado mediante diferentes métricas de clasificación, incluyendo:

* **Accuracy**
* **Matriz de confusión**
* **Precision y Recall**
* **F1-score**

Estas métricas permiten analizar qué tan bien el modelo logra identificar clientes que podrían cancelar el servicio.

---

## 📊 Resultados del análisis

El modelo desarrollado permite estimar la probabilidad de cancelación de clientes a partir de distintas características relacionadas con los servicios contratados y el comportamiento del cliente.

El análisis de las variables más influyentes muestra que factores como el **tipo de contrato**, el **tipo de servicio de internet** y los **cargos mensuales** tienen una influencia significativa en la probabilidad de churn.

Por ejemplo, los clientes con **contratos mensuales** tienden a presentar una mayor tasa de cancelación en comparación con aquellos que poseen contratos de mayor duración.

---

## 🧠 Conclusiones

Los resultados obtenidos demuestran cómo el uso de técnicas de análisis de datos y machine learning puede ayudar a las empresas a comprender mejor el comportamiento de sus clientes.

La capacidad de anticipar qué clientes tienen mayor probabilidad de cancelar el servicio permite a las empresas diseñar estrategias de retención más efectivas, como promociones personalizadas, mejoras en el servicio o programas de fidelización.

Este tipo de modelos puede convertirse en una herramienta clave para la toma de decisiones estratégicas en empresas orientadas al servicio.

---

## 📂 Estructura del proyecto

```
TelecomX-Churn-Prediction/
│
├── TelecomX_Churn_Model.ipynb
├── TelecomX_clean.csv
├── README.md
```

---

## 👩‍💻 Autor

Proyecto desarrollado como parte del **Challenge de Data Science de Alura LATAM**, enfocado en la aplicación de técnicas de análisis de datos, estadística y machine learning para resolver problemas reales de negocio.
