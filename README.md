# ✈️ British Airways Customer Booking Prediction (Forage Simulation)

Proyecto realizado como parte de la simulación de trabajo en ciencia de datos para British Airways en la plataforma Forage (julio de 2025).

## 📌 Objetivo

Predecir si un cliente completará la reserva de sus vacaciones usando datos históricos de comportamiento de reserva. Este proyecto busca ayudar a British Airways a identificar a clientes con alta intención de compra antes de que tomen su decisión final.

## 🧠 Lo que hice

- Exploración y análisis de un dataset con 50.000 registros.
- Ingeniería de variables: codificación de variables categóricas, selección de features y manejo del desbalance de clases.
- Entrenamiento de un modelo de clasificación con `RandomForestClassifier`.
- Validación cruzada y evaluación con métricas como ROC AUC, precisión, recall y matriz de confusión.
- Visualización de la importancia de variables para la toma de decisiones del negocio.
- Preparación de una presentación ejecutiva para comunicar hallazgos clave.

## 🧰 Tecnologías y librerías

- Python
- pandas, numpy
- scikit-learn
- seaborn, matplotlib

## 📊 Resultados del modelo

- **AUC (ROC):** 0.645
- **Accuracy:** 74.8%
- **Recall (compradores):** 42%
- **F1-score (compradores):** 0.33

> Se logró triplicar la tasa de detección de compradores con ajuste de clase (`class_weight='balanced'`), mejorando la utilidad del modelo en campañas proactivas.
