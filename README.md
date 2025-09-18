# Random_Forest

Detección de malware en dispositivos Android mediante el análisis del tráfico de red generado, usando un modelo basado en Random Forest.

---

## Descripción

Este proyecto implementa una metodología para identificar software malicioso en dispositivos Android analizando sus patrones de tráfico de red. Emplea Random Forest (subconjunto de árboles de decisión) para clasificar conexiones como benignas o maliciosas. El trabajo incluye el notebook con experimentos, las métricas, y la visualización de resultados.

---

## Estructura

- `RandomForest.ipynb` — Notebook principal donde se desarrollan los experimentos: carga del dataset, preprocesamiento, entrenamiento del modelo, evaluación y visualización de resultados.  
- `Url_Descarga_DataSet.txt` — enlace(s) para descargar el dataset que se utiliza en los experimentos.  
- `LICENSE` — archivo de licencia (GPL-3.0).  

---

## Requisitos

Para usar este proyecto necesitarás:

- Python 3.x  
- Librerías típicas de análisis de datos y aprendizaje automático (por ejemplo: `pandas`, `scikit-learn`, `matplotlib`, `seaborn` u otras usadas en el notebook).  
- Jupyter Notebook o similar para abrir y ejecutar `RandomForest.ipynb`.  
- Acceso al dataset (descargándolo desde la(s) URL(s) que aparece(n) en `Url_Descarga_DataSet.txt`).

---

## Uso

1. Clona el repositorio:

   ```bash
   git clone https://github.com/UrbanoTrejoOrlando/Random_Forest.git
   ```
2. Accede al directorio:
   ```bash
   cd Random_Forest
   ```  
3. Descarga el dataset:
    - Revisa el archivo Url_Descarga_DataSet.txt para obtener los enlaces.
    - Descarga y guarda los datos en una carpeta accesible para el notebook.

4. Abre el notebook:
   ```bash
    jupyter notebook RandomForest.ipynb
   ``` 
5. Dentro del notebook puedes:
   
  - Explorar los datos crudos: ver estadísticas, distribuciones, manejo de valores faltantes, etc.
  - Preprocesar los datos (normalización, codificación, selección de características, etc.).
  - Entrenar el modelo Random Forest.
  - Evaluar - usar métricas como precisión, recall, F1, curva ROC-AUC, etc.
  - Ajustar hiperparámetros si se desea (número de árboles, profundidad máxima, etc.).
  - Visualizar los resultados y compararlos.
