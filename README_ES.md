📌 Sobre el Proyecto

Este proyecto tiene como objetivo predecir la rotación de clientes (churn) de la operadora ficticia Interconnect, utilizando datos contractuales, personales y de servicios.

Además de la predicción, se realizó una clusterización de clientes para apoyar estrategias de segmentación y retención.

## 🗂️ Estructura de los Datos

Se utilizaron 4 conjuntos de datos:

- `personal.csv` → información personal de los clientes  
- `contract.csv` → tipo y duración del contrato, método de facturación, estado de churn  
- `internet.csv` → servicios de internet contratados  
- `phone.csv` → servicios de telefonía contratados  

## 🔎 Etapas del Proyecto

**Análisis Exploratorio de Datos (EDA)**

- Tratamiento de valores faltantes  
- Conversión de tipos de datos  
- Análisis de distribuciones y outliers  
- Estudio de correlaciones  

**Preprocesamiento**

- Normalización de variables numéricas  
- Codificación de variables categóricas (One-Hot Encoding)  
- División de los datos en entrenamiento y prueba con estratificación  

**Modelado**

- Regresión Logística  
- Random Forest  
- Gradient Boosting  

**Evaluación**

- Accuracy, Precision, Recall, F1-Score  
- Matriz de confusión  
- Informe de clasificación  

**Clusterización (extra)**

- Reducción de dimensionalidad con PCA  
- Agrupamiento de clientes mediante K-Means  

## 📊 Resultados Principales

- Gradient Boosting mostró el mejor desempeño en la prueba.  
- El modelo puede identificar clientes propensos al churn, permitiendo estrategias de retención más efectivas.  
- La clusterización reveló patrones de comportamiento útiles para campañas de marketing segmentadas.  

## 🛠️ Tecnologías Utilizadas

- Python (pandas, numpy, matplotlib, seaborn)  
- scikit-learn  
- PCA & K-Means  
