# 😀 Proyecto de Reconocimiento de Emociones con Deep Learning

Este proyecto implementa un clasificador de emociones faciales utilizando un dataset creado automáticamente con imágenes de Bing y un modelo de Transfer Learning con MobileNetV2.

---


## 🚀 Descripción
El sistema permite:
- 🔎 Descargar automáticamente imágenes de diferentes emociones desde Bing.
- 🖼️ Preprocesar el dataset con técnicas de data augmentation.
- 🤖 Entrenar un modelo de Red Neuronal Convolucional (CNN) basado en MobileNetV2.
- 🧪 Validar el rendimiento del modelo en un conjunto de prueba.
- 📷 Subir una imagen y predecir la emoción detectada (felicidad, tristeza, enojo o sorpresa).

## 🛠️ Tecnologías utilizadas
- Python 3.8+
- TensorFlow / Keras para construir y entrenar el modelo.
- Bing Image Downloader para recolectar imágenes automáticamente.
- NumPy, PIL y Matplotlib para el procesamiento y visualización de imágenes.
- Google Colab como entorno de desarrollo.

## 📂 Flujo de trabajo
- 📥 Descarga de imágenes desde Bing por categorías de emociones.
- 🧹 Preprocesamiento del dataset (escalado, rotación, flips, zoom, etc.).
- 🧠 Entrenamiento del modelo usando MobileNetV2 con fine-tuning parcial.
- 🧪 Validación con un conjunto separado del dataset.
- 📷 Predicción en imágenes subidas por el usuario.

## ⚙️ Requisitos previos
- Tener instalado tensorflow, numpy, matplotlib, pillow.
- Descargar el dataset con bing-image-downloader.
- Ejecutar en Google Colab o en un entorno local con GPU para acelerar el entrenamiento.

## 📑 Ejemplo de uso
- Subir una foto de una persona mostrando alguna emoción y el sistema la procesa devolviendo algo como:

```bash
🔍 Emoción detectada: FELICIDAD
```

## 🎯 Resultados
- Modelo entrenado con MobileNetV2 fine-tuning.
- Dataset balanceado de 4 clases principales:
  * 😀 Felicidad
  * 😢 Tristeza
  * 😡 Enojo
  * 😲 Sorpresa
