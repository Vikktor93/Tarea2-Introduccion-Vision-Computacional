<p align="left">
   <img src="https://img.shields.io/badge/Status-Terminado-green?style=plastic">
   <img src="https://img.shields.io/badge/Python-3776AB?style=plastic&logo=python&logoColor=white"/>
   <img src="https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=plastic&logo=TensorFlow&logoColor=white"/>
   <img src="https://img.shields.io/badge/Jupyter-%23e58f1a.svg?style=plastic&logo=Jupyter&logoColor=white"/>

<img src="./assets/banner-computer-vision2.png"/>

## 🌿**Tarea 2: Clasificación de imágenes con CNN**
Este repositorio contiene el desarrollo de la **Tarea 2** de la asignatura *Visión Computacional*, centrado en la implementación de una **Red Neuronal Convolucional (CNN)** para la clasificación automática de hojas de tomate sanas y enfermas por *Early Blight*, utilizando el dataset [PlantVillage](https://www.kaggle.com/datasets/emmarex/plantdisease).

### 🧪 **Descripción del trabajo**

- **Dataset:** PlantVillage (2 clases: `Tomato_healthy`, `Tomato_Early_blight`)
- **Imágenes utilizadas:** 200 imágenes preprocesadas en la Tarea 1 (100 por clase)
- **Modelo:** CNN con capas convolucionales, de max pooling, regularización mediante dropout y denses layers.
- **Preprocesamiento adicional:**
  - Normalización de pixeles
  - `Data augmentation` (rotaciones, desplazamientos, zoom, flip horizontal)
- **Evaluación:**
  - Precisión alcanzada: **89.47%**
  - Métricas: precisión, recall, F1-score (macro)
  - Tiempos de inferencia medidos en 5 ejecuciones con resumen estadístico
- **Visualización:** 
  - Evolución de `loss` y `accuracy` durante entrenamiento
  - Ejemplos de imágenes predichas (aciertos y errores)
- **Análisis crítico:** Reflexión sobre rendimiento, limitaciones del modelo, y sugerencias de mejora (más épocas, batch normalization, transfer learning)

### 📊 **Resultados destacados**

| Métrica               | Valor     |
|------------------------|-----------|
| Accuracy               | 89.47%    |
| Precision (macro)      | 91.3%     |
| Recall (macro)         | 89.5%     |
| F1-score (macro)       | 89.3%     |
| Tiempo promedio (s)    | 0.51      |
| Desv. estándar (s)     | 0.079     |

---

### ⚠️ **Requisitos**

Este proyecto requiere:

- Python 3.10+
- TensorFlow / Keras
- matplotlib
- pandas
- scikit-learn
- Jupyter Notebook

---

## 📄 Licencia

Este trabajo es de carácter académico y su uso está restringido exclusivamente para fines educativos.

El dataset utilizado proviene del repositorio [PlantVillage Dataset](https://github.com/spMohanty/PlantVillage-Dataset), desarrollado por Hughes & Salathé (2015).  
Por favor, cite el artículo correspondiente si reutiliza este dataset:

> Hughes, D. P., & Salathé, M. (2015). An open access repository of images on plant health to enable the development of mobile disease diagnostics. *arXiv preprint arXiv:1511.08060.*
