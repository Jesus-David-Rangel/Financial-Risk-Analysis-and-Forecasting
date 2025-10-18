### Análisis de Riesgo Financiero y Pronóstico de Series Temporales

**Descripción del Proyecto:**

Este proyecto se enfocó en el análisis y pronóstico de riesgo financiero centrado en un dataset de solicitudes de préstamo extraído de Kaggle. Incluye limpieza y normalización de variables (ingresos, deudas, ratios como DTI y utilización de tarjeta), análisis exploratorio, visualizaciones y tratamiento de valores atípicos y formatos numéricos inconsistentes. Se realizan ingeniería de características orientada a crédito (historial de pagos, duración de crédito, activos vs. pasivos) y estrategias para clases desbalanceadas. El objetivo principal es construir modelos supervisados para clasificación de aprobación/riesgo y modelos de regresión para tasas y pagos, evaluados con métricas técnicas (AUC, precisión/recall/F1, RMSE) y validación cruzada; además se incorpora interpretabilidad (feature importance, SHAP) y buenas prácticas de reproducibilidad en notebooks.

### Financial Risk Analysis and Time Series Forecasting

**Project Description**

This project implements an end-to-end financial risk and forecasting pipeline: data ingestion from Kaggle, robust preprocessing, and targeted feature engineering for credit scoring and exposure estimation. It trains and tunes supervised models (tree-based ensembles, logistic/linear baselines) for loan approval and risk scoring, plus regression models for interest/payment forecasting, using cross-validation and imbalance handling techniques. Evaluation focuses on business-relevant metrics (AUC for ranking, precision/recall for decisioning, RMSE for forecasts) and model explainability (feature importance, SHAP) to support transparent decisions. Notebooks are Colab-ready and organized for reproducibility, auditability, and easy extension toward deployment or further research.
