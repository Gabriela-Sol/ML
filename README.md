# 🧠 ML Stroke Prediction Project

Este repositorio contiene el flujo completo para el análisis y predicción de ACV (stroke) usando Python y scikit-learn.

## 📁 Estructura principal
- `notebooks/` — Jupyter Notebooks para cada etapa del flujo (EDA, procesamiento, modelado, evaluación)
- `datasets/` — Datasets originales y procesados
- `src/` — Código fuente reutilizable (si aplica)
- `requirements.txt` — Dependencias del proyecto
- `.gitignore` — Archivos y carpetas a ignorar por git

## 🚀 Cómo reproducir el entorno
1. **Clona el repositorio**
2. **Crea un entorno virtual:**
   ```bash
   python -m venv venv
   # En Windows:
   venv\Scripts\activate
   # En Mac/Linux:
   source venv/bin/activate
   ```
3. **Instala las dependencias:**
   ```bash
   pip install -r requirements.txt
   ```

## 📓 Notebooks recomendados
- `01_data_loading.ipynb` — Carga y exploración inicial de datos
- `02_data_processing_reordered_professional (1).ipynb` — Procesamiento y EDA profesional
- `03_model_training.ipynb` — Entrenamiento de modelos
- `04_model_evaluation.ipynb` — Evaluación de modelos

> **Tip:** Si encuentras notebooks duplicados o versiones viejas, utiliza solo los listados arriba para un flujo limpio y profesional.

## 📝 Notas
- No subas la carpeta `venv/` ni archivos grandes de datos al repo.
- Si agregas nuevas dependencias, actualiza `requirements.txt` con `pip freeze > requirements.txt`.

---

¡Listo para analizar y modelar! 🚀
