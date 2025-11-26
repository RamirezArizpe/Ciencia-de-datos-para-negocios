# Inteligencia Artificial  
Licenciatura en Ciencia de Datos para Negocios  
Universidad Nacional Rosario Castellanos  
Branch: UCA-Inteligencia-Artificial

---

## 1. Introducción

Este repositorio reúne los notebooks desarrollados en la Unidad de Aprendizaje Inteligencia Artificial, utilizando Google Colab como entorno de trabajo. El objetivo es documentar el proceso formativo mediante la implementación de distintos modelos de redes neuronales aplicados a problemas de clasificación y predicción.

El contenido está organizado de manera progresiva para facilitar la comprensión conceptual y práctica de las arquitecturas estudiadas: perceptrón, redes multicapa, redes convolucionales y redes recurrentes.

---

## 2. Clasificación en Inteligencia Artificial

La clasificación es una tarea supervisada en la cual un modelo aprende patrones a partir de datos etiquetados y los utiliza para asignar categorías a nuevos ejemplos. Esta tarea es fundamental en áreas como visión por computadora, diagnóstico, análisis de texto y predicción de comportamiento.

Las redes neuronales permiten abordar problemas de clasificación con distintos niveles de complejidad, dependiendo de la arquitectura utilizada.

---

## 3. Arquitecturas estudiadas

A continuación, se describen las características principales de cada arquitectura incluida en el repositorio.

### 3.1 Perceptrón

El perceptrón es el modelo básico de una red neuronal. Permite realizar clasificaciones lineales mediante el ajuste de pesos y una función de activación.

**Características principales:**

| Aspecto | Descripción |
|--------|-------------|
| Tipo de modelo | Lineal |
| Tipo de problemas | Clasificación binaria lineal |
| Función clave | Regla delta y ajuste de pesos |
| Limitaciones | No resuelve problemas no lineales |

**Notebooks incluidos:**

- Perceptrón – AND  
  https://github.com/RamirezArizpe/.../Perceptrón_Ejemplo_AND.ipynb  
- Perceptrón – OR  
  https://github.com/RamirezArizpe/.../Perceptrón_Ejemplo_OR.ipynb  
- Perceptrón – NOT  
  https://github.com/RamirezArizpe/.../Perceptrón_Ejemplo_NOT.ipynb

---

### 3.2 Redes Neuronales Multicapa (MLP)

Las redes multicapa introducen capas ocultas y funciones de activación no lineales, permitiendo aprender relaciones complejas entre variables.

**Características principales:**

| Aspecto | Descripción |
|--------|-------------|
| Capacidad | Modela relaciones no lineales |
| Aplicaciones comunes | Clasificación y regresión |
| Requisitos | Normalización de datos |
| Desafíos | Ajuste de hiperparámetros |

**Notebooks incluidos:**

- Clasificación de candidatos  
  https://github.com/RamirezArizpe/.../Clasificación_de_candidatos.ipynb  
- Predicción de eficiencia de combustible  
  https://github.com/RamirezArizpe/.../Predicción_de_la_eficiencia_de_combustible.ipynb  
- Predicción de popularidad en Spotify  
  https://github.com/RamirezArizpe/.../Predicción_de_popularidad_de_spotify.ipynb  
- Red multicapa para predicción de depresión  
  https://github.com/RamirezArizpe/.../Red_multicapa_depresión.ipynb

---

### 3.3 Redes Convolucionales (CNN)

Las redes convolucionales están diseñadas para procesar datos con estructura espacial, principalmente imágenes, mediante filtros que extraen patrones locales.

**Características principales:**

| Aspecto | Descripción |
|--------|-------------|
| Tipo de datos | Imágenes |
| Elementos clave | Convoluciones, kernels, pooling |
| Ventaja | Extrae características sin ingeniería manual |
| Aplicaciones | Reconocimiento visual y visión por computadora |

**Notebooks incluidos:**

- Clasificación de dígitos (MNIST)  
  https://github.com/RamirezArizpe/.../Clasificación_de_dígitos.ipynb  
- Clasificación de ropa (Fashion MNIST)  
  https://github.com/RamirezArizpe/.../Clasificación_de_ropa.ipynb

---

### 3.4 Redes Recurrentes (RNN)

Las redes recurrentes permiten modelar secuencias y dependencias temporales mediante retroalimentación en sus conexiones.

**Características principales:**

| Aspecto | Descripción |
|--------|-------------|
| Tipo de datos | Series temporales o secuencias |
| Elemento clave | Dependencia del estado previo |
| Uso común | Predicción de valores futuros |
| Limitaciones | Sensibles a gradientes explosivos o vanishing |

**Notebook incluido:**

- Predicción del precio del Bitcoin  
  https://github.com/RamirezArizpe/.../Predicción_precio_de_Bitcoin.ipynb

---

## 4. Herramientas utilizadas

Los notebooks fueron desarrollados íntegramente en Google Colab utilizando:

| Herramienta | Uso |
|-------------|-----|
| Python | Desarrollo de modelos |
| NumPy y Pandas | Manipulación y análisis de datos |
| Matplotlib | Visualización |
| Scikit-Learn | Preprocesamiento y métricas |
| TensorFlow / Keras | Construcción de redes neuronales |
| Google Drive | Lectura y escritura de archivos |

---

## 5. Estructura del repositorio

| Carpeta | Contenido |
|---------|-----------|
| Perceptrón | Modelos lineales básicos |
| Redes neuronales multicapa | MLP y variantes aplicadas |
| Convolusionales | CNN para clasificación de imágenes |
| Redes recurrentes | Modelos para series de tiempo |

---

## 6. Observaciones finales

El repositorio documenta la progresión del estudio de redes neuronales aplicadas a problemas reales de clasificación y predicción. Cada notebook incluye ejecución completa, comentarios explicativos y resultados seleccionados para facilitar su revisión académica.

