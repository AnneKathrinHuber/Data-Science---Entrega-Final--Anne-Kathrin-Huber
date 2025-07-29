# 🏦 Trabajo Final: Ingenia-2025  
## Detección de fraudes en transacciones bancarias

---

### 👥 Integrantes Grupo 4
- Carpio , Vanessa
- Huber , Anne Kathrin
- Siarri , Maria Florencia

---

## 📖 Introducción
Este proyecto es parte del **Trabajo Final** del curso de **Data Science** dictado por Fundación YPF en 2025.  
El pago en línea es el método de transacción más popular en el mundo, pero su auge trae consigo un incremento de fraude.  
El objetivo de este análisis es identificar **pagos fraudulentos** y **no fraudulentos** a partir de un conjunto de datos histórico proveniente de Kaggle.

---

## 🎯 Objetivos
1. Desarrollar un **modelo** que detecte transacciones potencialmente fraudulentas.  
2. Analizar distintos tipos de transacciones (`CASH-IN`, `CASH-OUT`, `DEBIT`, `PAYMENT`, `TRANSFER`).  
3. Explorar comportamientos según:
   - Montos
   - Días y horarios
   - Cuentas afectadas y destinos de las transferencias  

---

## 🚀 Metodología
- **Lenguaje y librerías**:  
  - Python: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  
- **Pasos**:  
  1. Carga y Preprocesamiento (escalado, separación de etiquetas)  
  2. Reducción de Dimensionalidad con PCA  
  3. Búsqueda de Parámetros para K-Means (Elbow y Silhouette)  
  4. Entrenamiento Final de K-Means y evaluación de la tasa de fraude en cada cluster  
  5. Estimación de ε y Ejecución de DBSCAN, con gráfico de k-distancia para seleccionar eps
  6. IsolationForest para scoring de anomalías
  7. Evaluación y Combinación de Señales de los métodos
  
---

## 🔗 Enlaces útiles
- 🔍 Dataset en Kaggle:  
  https://www.kaggle.com/datasets/rupakroy/online-payments-fraud-detection-dataset  
