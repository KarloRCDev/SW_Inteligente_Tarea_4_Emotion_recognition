# SW_Inteligente_Tarea_4_Emotion_recognition

Este repositorio contiene un proyecto de reconocimiento de emociones utilizando técnicas de aprendizaje profundo. Se han desarrollado tres notebooks que abarcan el entrenamiento de un modelo, así como la detección de emociones en imágenes y en tiempo real utilizando una cámara.

## Contenido del Repositorio

- **notebooks/**

  - **model_generator.ipynb**: Código para entrenar el modelo de reconocimiento de emociones.
  - **recognition_of_emotions.ipynb**: Código para reconocer emociones a partir de imágenes estáticas.
  - **recognition_of_emotions_real_time.ipynb**: Código para reconocer emociones en tiempo real utilizando una cámara.

- **data/**: Contiene las imágenes de entrenamiento y prueba, organizadas en carpetas por categoría de emoción.

- **real_test/**: Carpeta para almacenar imágenes que se usarán para pruebas en tiempo real.

- **model/**: Carpeta que contiene el modelo entrenado y otros recursos relacionados.

## Instalación

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/KarloRCDev/SW_Inteligente_Tarea_4_Emotion_recognition.git
   ```

2. Asegúrate de tener instaladas las siguientes dependencias:

- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib (opcional para visualización)

Puedes instalar las dependencias necesarias usando pip:

```bash
pip install tensorflow keras opencv-python numpy matplotlib
```

## Uso

1. Entrenamiento del Modelo

- Abre el notebook model_generator.ipynb.
- Ejecuta las celdas para cargar los datos, definir la arquitectura del modelo y entrenarlo.

2. Reconocimiento de Emociones en Imágenes

- Abre el notebook recognition_of_emotions.ipynb.
- Carga una imagen de prueba y ejecuta las celdas para predecir la emoción en la imagen.

3. Reconocimiento de Emociones en Tiempo Real

- Abre el notebook recognition_of_emotions_real_time.ipynb.
- Ejecuta el código para comenzar a detectar emociones en tiempo real a través de tu cámara.

#Resultados

- El modelo ha sido evaluado utilizando varias métricas, y los resultados se pueden revisar en los notebooks correspondientes. Las métricas incluyen precisión, recall y F1-score, que se muestran en una matriz de confusión.
