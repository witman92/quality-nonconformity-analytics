# Analítica de no conformidades y auditorías en planta de alimentos (2019-2025)

Análisis exploratorio y visual de los registros de auditorías y análisis de causa de no conformidades de una planta de alimentos (exportados desde SAP), orientado a encontrar patrones, cuellos de botella y focos de mejora en el sistema de calidad.

<img width="791" height="502" alt="Visualización del análisis" src="https://github.com/user-attachments/assets/e6a3fc5f-e035-4988-80c3-6b4adb60ae5b" />

## Qué incluye
- Estado de las auditorías por tipo (casinos, Food Defense, etc.): concluidas, pendientes y creadas.
- Conteo y **evolución mensual de no conformidades por área** (2019-2025).
- Factores que explican los **picos de no conformidades en 2025**.
- Distribución y densidad por área, más análisis de correlación.
- **Clustering con t-SNE 3D** (pipeline de scikit-learn) y caracterización de los clústeres.
- Hallazgos clave y próximos pasos.

## Estructura
```
nonconformity_analytics.ipynb
Registo exportado de sap de analis causa 2019-2025 (2).XLSX
```

**Stack:** Python · pandas · scikit-learn (t-SNE, ColumnTransformer) · Matplotlib · Seaborn
