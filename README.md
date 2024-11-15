# RIS_TFM_Ismael  

Este repositorio contiene el código desarrollado para el Trabajo de Fin de Máster (TFM) titulado *Uso de redes de base radial para almacenamiento de patrones de control de superficies inteligentes reconfigurables*.  

## Descripción  
El proyecto tiene como objetivo implementar y analizar Redes de Funciones de Base Radial (RBF) para modelar la relación entre ángulos de entrada y configuraciones de salida de superficies inteligentes reconfigurables. Los datos de entrada consisten en pares de ángulos, mientras que las salidas son matrices que representan configuraciones específicas de las RIS.  

El repositorio incluye:  
- **Implementación de la red RBF:** Desarrollo de la clase RBFNetwork con métodos para entrenamiento y predicción.  
- **Procesamiento de datos:** Normalización y aplicación de la Transformada Discreta del Coseno (DCT) para facilitar el aprendizaje.  
- **Entrenamiento y evaluación del modelo:** Uso de métricas como el Error Cuadrático Medio (MSE), el Error Absoluto Medio (MAE) y el Coeficiente de Determinación (R²).  
- **Visualización de resultados:** Gráficos y análisis para interpretar el rendimiento del modelo.  

---


---

## Requisitos Previos  
Para ejecutar el código, necesitas:  
- **Python 3.8 o superior.**  
- **Bibliotecas necesarias:**  
  - NumPy: Para operaciones matemáticas y manejo de arrays.  
  - SciPy: Para cargar archivos `.mat` y realizar la Transformada Discreta del Coseno (DCT).  
  - Pandas: Manipulación y análisis de datos.  
  - Scikit-learn: Implementación de algoritmos de aprendizaje automático.  
  - Matplotlib: Visualización de datos y resultados.  
  - Seaborn: Gráficos estadísticos avanzados.  
  - XlsxWriter: Generación de archivos Excel para exportar resultados.  

---

## Instalación  
1. Clona el repositorio:  
   git clone https://github.com/ismaelac8/RIS_TFM_Ismael.git

2. Instala las dependencias:
   pip install -r requirements.txt


El archivo a ejecutar es RIS_Notebook.ipynb.
