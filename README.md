# Churn Fintech Model

Modelo de predicción de abandono de clientes (churn) para una fintech, con Random Forest.
*Customer churn prediction model for a fintech use case, built with Random Forest.*

> **Nota:** es un proyecto de aprendizaje. Usa **datos sintéticos** y lo desarrollé apoyándome en herramientas de IA para aprender el flujo completo de un modelo de clasificación. No es un modelo en producción.

## Qué problema resuelve

Retener a un cliente cuesta menos que conseguir uno nuevo. El objetivo es identificar qué clientes tienen más probabilidad de abandonar el servicio para que el negocio pueda actuar antes.

## Qué hace el proyecto

1. **Análisis exploratorio (EDA):** distribución de variables, valores faltantes y relación con el churn.
2. **Ingeniería de variables** 
3. **Modelo:** clasificador Random Forest con scikit-learn.
4. **Validación:** separación entrenamiento/prueba y métricas de evaluación.
5. **Interpretación:** qué variables pesan más y qué significan para el negocio.

## Resultado

- **AUC-ROC: 0.937** sobre los datos sintéticos.
- Como los datos son sintéticos, esta cifra sirve para demostrar el flujo y **no debe tomarse como el rendimiento esperado con datos reales**.


## Tecnologías

Python · pandas · numpy · scikit-learn · matplotlib · Google Colab

## Cómo correrlo

1. Abre el notebook `churn_fintech_model.ipynb` en Google Colab o Jupyter.
2. Ejecuta las celdas en orden.

## Próximos pasos

- Probarlo con un dataset público real (por ejemplo, Telco Customer Churn de IBM).
- Comparar con regresión logística y gradient boosting.
- Probar umbrales de decisión según el costo de perder un cliente.

## Autora

**Sayuri Mota** · [LinkedIn](https://www.linkedin.com/in/ingrid-sayuri-mota-de-la-rosa) · [GitHub](https://github.com/Say1309)
