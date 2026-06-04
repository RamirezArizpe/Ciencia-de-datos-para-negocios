# Mercado Justo: Predicción del Precio Nacional del Maíz Blanco en México (2000–2026)

## Descripción del proyecto

Este repositorio contiene el desarrollo de un modelo de análisis y predicción del precio nacional del maíz blanco en México, integrando información histórica de mercado, variables macroeconómicas y factores climáticos.

El proyecto fue desarrollado como evidencia integradora para la Licenciatura en Ciencia de Datos para Negocios, aplicando metodologías de Minería de Datos, Series de Tiempo, Machine Learning y Analítica Predictiva.

El objetivo principal es construir una herramienta de apoyo para la toma de decisiones de productores, comercializadores y consumidores, permitiendo anticipar tendencias de precio y comprender los factores que influyen en su comportamiento.

---

## Objetivos

### Objetivo general

Desarrollar un modelo predictivo capaz de estimar el precio nacional del maíz blanco mediante el análisis de variables económicas, climáticas y de mercado.

### Objetivos específicos

* Analizar la evolución histórica del precio del maíz blanco en México.
* Integrar variables exógenas relevantes para explicar el comportamiento del mercado.
* Comparar distintos enfoques de modelado predictivo.
* Evaluar el desempeño de los modelos mediante métricas estadísticas.
* Generar recomendaciones para la toma de decisiones comerciales.

---

## Metodología

El proyecto sigue la metodología **CRISP-DM (Cross Industry Standard Process for Data Mining)**:

1. Comprensión del negocio.
2. Comprensión de los datos.
3. Preparación de los datos.
4. Modelado.
5. Evaluación.
6. Implementación y recomendaciones.

---

## Fuentes de datos

Se integraron distintas fuentes públicas y especializadas:

### Mercado agroalimentario

* Sistema Nacional de Información e Integración de Mercados (SNIIM)
* Precios históricos del maíz blanco
* Precios históricos de la tortilla

### Variables macroeconómicas

* Tipo de cambio Peso–Dólar
* Índice Nacional de Precios al Consumidor (INPC)
* Precio internacional del maíz (CBOT)

### Variables energéticas

* Precio del diésel

### Variables climáticas

* Temperatura promedio nacional
* Precipitación acumulada
* Índices de sequía

---

## Estructura del repositorio

```text
.
├── panorama_maizblanco_2000_2026.csv
├── Precio_tortilla_prom_nacional_2000_2026.csv
├── ModeloPrediccionAgropecuaria.tex
├── notebook principal
├── imágenes y gráficas generadas
└── documentación del proyecto
```

### Archivos principales

#### panorama_maizblanco_2000_2026.csv

Base consolidada del proyecto que contiene:

* Precio nacional del maíz blanco
* Variables económicas
* Variables climáticas
* Variables energéticas
* Variables de mercado

Periodo cubierto:

**2000–2026**

---

#### Precio_tortilla_prom_nacional_2000_2026.csv

Serie histórica utilizada para análisis comparativos entre:

* Precio del maíz
* Precio de la tortilla

Periodo cubierto:

**2000–2026**

---

#### ModeloPrediccionAgropecuaria.tex

Documento técnico completo del proyecto elaborado en LaTeX.

Incluye:

* Marco metodológico
* Análisis exploratorio
* Modelado estadístico
* Resultados
* Discusión
* Conclusiones

---

## Técnicas utilizadas

### Análisis exploratorio de datos (EDA)

* Estadística descriptiva
* Distribuciones
* Correlaciones
* Visualización temporal

### Minería de datos

* Reglas de asociación (Apriori)
* Identificación de patrones de mercado

### Machine Learning

* Regresión Lineal
* Regresión Polinomial
* Árboles de Decisión
* Random Forest
* XGBoost

### Series de tiempo

* ARIMA
* SARIMA
* ARIMAX
* SARIMAX

---

## Métricas de evaluación

Los modelos fueron evaluados mediante:

* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)
* MSE (Mean Squared Error)
* R² (Coeficiente de determinación)

---

## Principales hallazgos

* El precio nacional del maíz presenta una tendencia creciente de largo plazo.
* El tipo de cambio y el precio internacional del maíz muestran una influencia importante sobre el mercado nacional.
* Las variables climáticas aportan capacidad explicativa adicional.
* Los modelos basados en ensambles presentan mejor desempeño predictivo que los modelos lineales simples.
* Los modelos SARIMAX permiten capturar simultáneamente la dinámica temporal y el efecto de variables externas.

---

## Tecnologías utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Statsmodels
* PySpark
* Jupyter Notebook
* LaTeX

---

## Aplicaciones potenciales

* Planeación agrícola.
* Pronóstico de precios.
* Inteligencia de mercados.
* Diseño de políticas públicas.
* Gestión de riesgos agroalimentarios.
* Apoyo a productores y comercializadores.

---

## Autor

**Marco Ramírez Arizpe**

Licenciatura en Ciencia de Datos para Negocios

Universidad Nacional Rosario Castellanos

Ciudad de México, México

---

## Licencia

Este proyecto tiene fines académicos y de investigación.

Los datos utilizados provienen de fuentes públicas y conservan las restricciones y condiciones establecidas por sus respectivas instituciones de origen.
