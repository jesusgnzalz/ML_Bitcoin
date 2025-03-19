# Predicción del Precio de Bitcoin con Machine Learning

## 📌 Descripción del Proyecto
Este proyecto tiene como objetivo predecir el precio de Bitcoin utilizando algoritmos de **Machine Learning tradicional**, basados en datos históricos. Se trabajó con un **dataset reducido** para mejorar el rendimiento y facilitar el entrenamiento del modelo.

## 📌 Problema a Resolver
El precio de Bitcoin es altamente volátil y depende de múltiples factores. Nuestro objetivo es construir un modelo que, basándose en variables como el precio de apertura, el precio máximo/mínimo y el volumen de transacciones, pueda hacer una predicción del precio de cierre con **cierta precisión**.

## 📌 Dataset Utilizado
- **Fuente:** El dataset original proviene de [Kaggle](https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data).
- **Descripción:** Contiene datos históricos de Bitcoin, incluyendo el precio de apertura, máximo, mínimo, cierre y volumen de transacciones.
- **Versión Reducida:** Se ha tomado una muestra aleatoria del dataset original para optimizar los tiempos de entrenamiento.
- **Acceso:** Puedes descargar el dataset original en el enlace de Kaggle.

## 📌 Solución Adoptada
1. **Exploración de Datos (EDA):** Análisis de las correlaciones entre variables y limpieza de datos.
2. **Preprocesamiento:** Normalización y separación de datos en entrenamiento y test.
3. **Modelos Usados:**
   - **Regresión Lineal** para una predicción base.
   - **Random Forest Regressor** como modelo más robusto.
4. **Evaluación del Modelo:** Comparación de métricas como MAE, MSE y R².
5. **Almacenamiento del Modelo:** Se guarda el mejor modelo en formato `.joblib`.

## 📌 Estructura del Repositorio
ML_Bitcoin/
│── src/
│   ├── data_sample/        # Muestra del dataset utilizado en el proyecto
│   ├── img/                # Imágenes generadas para análisis y presentación
│   ├── notebooks/          # Notebooks con pruebas y análisis
│   ├── results_notebook/   # Notebook final con el modelo completo
│   ├── models/             # Modelos guardados después del entrenamiento
│   ├── utils/              # Funciones auxiliares utilizadas en el proyecto
│── README.md               # Descripción del proyecto
│── requirements.txt        # Librerías necesarias para ejecutar el proyecto
│── presentation.pptx       # Presentación para la exposición final
│── .gitignore              # Archivos y carpetas excluidos del repositorio
