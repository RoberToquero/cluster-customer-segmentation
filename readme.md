# 🧩 Customer Segmentation - Clustering Analysis

Este proyecto tiene como objetivo aplicar técnicas de **aprendizaje no supervisado** para segmentar a los clientes de un centro comercial en grupos con características similares, permitiendo comprender mejor sus comportamientos y preferencias.

---

## 📊 Descripción del dataset

Se utiliza el dataset **Customer Segmentation** disponible en [Kaggle](https://www.kaggle.com/datasets/abisheksudarshan/customer-segmentation).

El conjunto de datos contiene información sobre los clientes, incluyendo:

- **Gender**: género del cliente  
- **Age**: edad  
- **Annual Income (k$)**: ingresos anuales  
- **Spending Score (1–100)**: puntuación de gasto otorgada por el centro comercial  

---

## 🧠 Objetivo del proyecto

Segmentar a los clientes en grupos homogéneos utilizando técnicas de clustering, con el fin de:

- Identificar patrones de comportamiento y gasto  
- Comprender las características de cada grupo  
- Facilitar la toma de decisiones en estrategias de marketing o fidelización  

---

## 🚀 Pasos realizados

1. **Exploración de datos (EDA)**  
   - Análisis descriptivo de las variables  
   - Detección de valores atípicos  
   - Visualización de distribuciones y relaciones  

2. **Preprocesamiento de datos**  
   - Limpieza y normalización de variables  
   - Escalado con `StandardScaler` o `MinMaxScaler`  
   - Reducción de dimensionalidad con **PCA** (si aplica)

3. **Modelado (Clustering)**  
   - Aplicación de diferentes algoritmos:
     - **K-Means**
     - **DBSCAN**
     - **Clustering jerárquico**
   - Comparación de los resultados y visualización de los grupos formados

4. **Evaluación**  
   - Cálculo de métricas como el **índice de Silhouette** y la **inercia** (para K-Means)
   - Interpretación visual en 2D y 3D de los clusters

5. **Conclusiones**  
   - Análisis de los distintos grupos formados  
   - Reflexión sobre cómo esta segmentación podría aplicarse en estrategias de marketing y atención al cliente

---

## 🧰 Tecnologías utilizadas

- P
