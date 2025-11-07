# Machine-Learning
Proyecto de Machine Learning para análisis y predicción desarrollado durante el programa de Data Science en TripleTen.
# 🤖 Customer Churn Prediction – Machine Learning Project

Este proyecto forma parte del programa de **Data Science en TripleTen**.  
El objetivo es predecir la **fuga de clientes (churn)** en el banco **Beta Bank**, utilizando modelos de *Machine Learning* supervisado.

---

## 🎯 Objetivo del proyecto

Desarrollar un modelo predictivo que permita identificar qué clientes tienen mayor probabilidad de abandonar el banco, con el fin de apoyar estrategias de retención.

---

## 📊 Dataset

El conjunto de datos contiene información como:

- Género  
- Edad  
- Estado civil  
- Años como cliente  
- Balance promedio  
- Número de productos contratados  
- Actividad bancaria  
- Indicador de churn (0 = cliente permanece, 1 = cliente abandona)

---

## 🧠 Procesos realizados

### ✅ Análisis exploratorio (EDA)
- Revisión de valores faltantes  
- Identificación de patrones  
- Estadísticas descriptivas  
- Visualizaciones de relaciones entre variables  

### ✅ Preparación de datos
- Codificación de variables categóricas  
- Estandarización  
- División en train/test  
- Manejo del desbalance mediante oversampling  

### ✅ Modelos aplicados
- Regresión Logística  
- Árbol de Decisión  
- Random Forest  
- Gradient Boosting  

Métricas utilizadas:
- Accuracy  
- Recall  
- Precision  
- **F1-score**  
- Matriz de confusión  

*(Puedes actualizar el F1-score real de tu notebook si quieres.)*

---

## ✅ Resultados principales

- El modelo optimizado obtuvo un **F1-score sólido**, superando la línea base.  
- Los métodos basados en árboles mostraron mejor desempeño que la regresión logística.  
- Se identificaron variables clave relacionadas con la fuga de clientes.

---

## 📁 Archivos incluidos

- `Aprendizaje supervisado.ipynb` — Notebook principal  
- `README.md` — Documentación del proyecto  

---

## 🚀 Cómo ejecutar

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Jeanems/customer-churn-prediction-ml.git
