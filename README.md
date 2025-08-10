# 📊 Predicción y Análisis de Churn en Clientes - Telecom X

Este trabajo tiene como propósito descubrir los factores clave que influyen en la **pérdida de clientes (churn)** en Telecom X.  
A partir de un dataset real, se realizó un análisis exploratorio exhaustivo y se entrenaron diferentes modelos de machine learning con el fin de **anticipar la cancelación de contratos y proponer estrategias de retención**.

---

## 📦 Principales librerías utilizadas

- **pandas**, **numpy** → Manipulación y análisis de datos
- **matplotlib**, **seaborn**, **plotly** → Visualización estática e interactiva
- **scikit-learn** → Entrenamiento y evaluación de modelos
- **xgboost** → Modelo de gradiente boosting optimizado

---

## 📂 Estructura del proyecto

1. **Exploración inicial (EDA)**  
   - Revisión general del dataset  
   - Análisis de distribución de variables  
   - Visualización de tasas de churn  

2. **Preparación de datos**  
   - Limpieza y tratamiento de valores faltantes  
   - Codificación de variables categóricas  
   - Normalización de variables numéricas  

3. **Entrenamiento de modelos de clasificación**  
   - **K-Nearest Neighbors (KNN)**  
   - **Random Forest**  
   - **Regresión Logística**  
   - **Support Vector Machine (SVM)**  
   - **XGBoost**  

4. **Evaluación de modelos**  
   - Métricas de precisión, recall y F1-score  
   - Matrices de confusión  
   - Comparación de rendimiento  

5. **Identificación de variables relevantes**  
   - Importancia de características por modelo  
   - Comparación entre algoritmos  

---

## 📊 Variables Analizadas

Entre las variables más estudiadas se encuentran:
- Tiempo como cliente (tenure)
- Tipos de servicios contratados (Internet, telefonía, streaming)
- Modalidades de pago
- Facturación mensual y total
- Interacciones con servicio técnico

## 🔑 Principales hallazgos

Los modelos coinciden en que los factores más determinantes son:
- **Antigüedad del cliente**: mayor riesgo de churn en los primeros meses.
- **Calidad del soporte técnico**: problemas no resueltos aumentan la fuga.
- **Claridad en facturación**: cobros poco transparentes afectan la confianza.
- **Uso de servicios extra**: menor adopción se asocia a mayor probabilidad de baja.

---

## 📌 Recomendaciones estratégicas

1. **Programas de fidelización para nuevos clientes**  
2. **Mejorar tiempos y calidad en soporte técnico**  
3. **Políticas de precios claras y transparentes**  
4. **Promoción de servicios adicionales para aumentar engagement**

Con estas acciones, **Telecom X** podría reducir su tasa de cancelación y aumentar la retención a largo plazo.

---

## 📁 Archivos del proyecto

- `TelecomX_LATAM.ipynb` → Notebook con el desarrollo completo de modelos  
- `README.md` → Documento explicativo
