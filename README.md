# Proyecto de IA - Predicción de Accidentes Cerebrovasculares

Este repositorio contiene un proyecto de inteligencia artificial para predecir accidentes cerebrovasculares utilizando machine learning. Utilizamos el dataset de Kaggle: [Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset).

## Estructura del Proyecto

- `datasets/`: Contiene el dataset `healthcare-dataset-stroke-data.csv` descargado de Kaggle.
- `notebooks/`: Notebooks de Jupyter para análisis de datos, preprocesamiento y entrenamiento de modelos.
  - `01_data_loading.ipynb`: Carga y exploración inicial de datos.
  - `02_data_preprocessing.ipynb`: Limpieza y preprocesamiento de datos.
  - `03_model_training.ipynb`: Entrenamiento de modelos ML (Logistic Regression, Random Forest, SVM).
  - `04_model_evaluation.ipynb`: Evaluación y comparación de modelos.
- `src/`: Código fuente adicional, como scripts de utilidad o módulos personalizados.
- `models/`: Modelos entrenados guardados (ej. `modelo_stroke_rf.pkl`).
- `requirements.txt`: Lista de dependencias de Python necesarias.
- `.gitignore`: Archivos a ignorar en el control de versiones.

## Dataset

El dataset contiene información médica de pacientes con las siguientes características:
- `id`: Identificador único
- `gender`: Género
- `age`: Edad
- `hypertension`: Hipertensión (0/1)
- `heart_disease`: Enfermedad cardíaca (0/1)
- `ever_married`: Si ha estado casado
- `work_type`: Tipo de trabajo
- `Residence_type`: Tipo de residencia
- `avg_glucose_level`: Nivel promedio de glucosa
- `bmi`: Índice de masa corporal
- `smoking_status`: Estado de fumador
- `stroke`: Variable objetivo (0/1) - si sufrió un accidente cerebrovascular

## Instalación

1. Clona este repositorio.
2. Instala las dependencias: `pip install -r requirements.txt`.
3. Abre los notebooks en Jupyter o VS Code para ejecutar el código.

## Uso

- Los notebooks están organizados en secuencia para un flujo completo de ML.
- Comienza con `01_data_loading.ipynb` para explorar los datos.
- Ejecuta `02_data_preprocessing.ipynb` para preparar los datos.
- Entrena modelos en `03_model_training.ipynb`.
- Evalúa los resultados en `04_model_evaluation.ipynb`.
- Los modelos entrenados se guardan en `models/`.

## Resultados Esperados

Dado que es un dataset desbalanceado (pocos casos positivos de stroke), se espera:
- Alta accuracy pero baja recall para la clase positiva.
- Uso de métricas como ROC AUC para evaluación más precisa.
- Técnicas como SMOTE podrían mejorar el rendimiento en futuras iteraciones.

## Contribución

Si deseas contribuir, por favor crea un pull request con tus cambios.