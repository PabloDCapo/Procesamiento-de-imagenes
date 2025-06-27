## Trabajo Final: Detección de Semáforos y Clasificación de Estado con Visión por Computadora

Este trabajo consiste en el desarrollo de un sistema capaz de detectar semáforos en imágenes urbanas y determinar su estado (rojo, amarillo o verde). Se trabajó a partir del dataset **LISA Traffic Light Dataset**, y se implementaron dos enfoques complementarios:

1. Un enfoque basado en **segmentación de color HSV** para identificar regiones compatibles con luces de semáforos.
2. Un enfoque más robusto utilizando el modelo **YOLOv8 preentrenado**, que detecta semáforos mediante bounding boxes.

La combinación de ambos permitió lograr una solución funcional, que identifica la presencia de semáforos en imágenes nuevas y clasifica el color de la luz visible.

## Objetivos

- Detectar la presencia de semáforos en imágenes urbanas.
- Localizar su posición mediante bounding boxes.
- Clasificar su estado como **rojo**, **amarillo** o **verde** utilizando análisis de color.
- Probar la solución tanto en imágenes anotadas como en imágenes nuevas.
- Evaluar un enfoque inicial tradicional (segmentación de color) y compararlo con una solución moderna basada en deep learning (YOLOv8).
- Integrar todo en una interfaz interactiva con **Gradio**.


## Tecnologías y librerías utilizadas

- `OpenCV` para procesamiento de imágenes y visualización.
- `NumPy` y `Pandas` para manejo de datos.
- `Matplotlib` para visualización en el notebook.
- `Ultralytics` (YOLOv8) para detección de objetos preentrenada.
- `Gradio` para construcción de una demo interactiva.
- `kagglehub` para descarga directa del dataset desde Kaggle.

## ¿Cómo usar el notebook?

- Abrir en Google Colab y ejecutar las celdas en orden.
- Se puede cargar cualquier imagen urbana desde el Colab o usar la interfaz Gradio integrada.

