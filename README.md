# README — Predicción de Tarifas (NYC/Uber)

## Integrantes
- Esteva Matias
- Prieto Tobias

## Descripcion

Proyecto para predecir **`fare_amount`** (tarifa) de viajes en NYC usando aprendizaje automático. Se trabaja con fechas, coordenadas y algunas variables derivadas (hora/día, distancia, etc.).

## Qué incluye

* Notebook para **EDA**, **preprocesamiento**, **modelado** y **comparación**.
* Métricas y gráficos básicos (RMSE, MAE, R², residuos, real vs. predicho).


## Librerías utilizadas

* **pandas** — manejo de datos y DataFrames.
* **numpy** — operaciones numéricas y vectorización.
* **scikit-learn** — modelado (LinearRegression, Ridge, Lasso, ElasticNet), métricas y `train_test_split`.
* **matplotlib** — gráficos base (residuos, real vs. predicho).
* **seaborn** — visualizaciones rápidas y estéticas.
* **holidays** — marcar feriados de EE. UU. (`holidays.US()`).
* **time**  - manejo de tiempos de ejecución.
* **haversine** - distancias entre puntos de una esfera.

### Instalación rápida

```bash
pip install pandas numpy scikit-learn matplotlib seaborn holidays time
```



