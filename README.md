# Telecom X — Churn (ETL + EDA + Modelado)

Este proyecto utiliza el **dataset del proyecto anterior** para construir un pipeline de **predicción de cancelación**.

## Pasos
1. **ETL** desde JSON (aplanado con `pandas.json_normalize`), renombrado y tipificación.
2. **EDA** con gráficos clave (contrato, internet, correlaciones).
3. **Modelado** con Regresión Logística y RandomForest:
   - Métricas: Accuracy, Precision, Recall, F1, ROC AUC, PR AUC.
   - Curvas ROC.
   - Importancia de variables: coeficientes y permutation importance.
4. **Conclusiones** y recomendaciones de retención.

## Uso en Google Colab
1. Sube el notebook `TelecomX_Churn_Modeling.ipynb` a Colab.
2. Cambia la variable `api_url` por tu **link RAW** del JSON del proyecto anterior.
3. Ejecuta **Run all**.

## Requisitos
- Python 3, pandas, numpy, matplotlib, scikit-learn, requests (y opcional seaborn).

