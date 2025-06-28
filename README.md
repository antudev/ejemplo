# 🕹️ Clasificador de Imágenes de Videojuegos

Este proyecto utiliza un modelo de aprendizaje profundo entrenado con TensorFlow/Keras para **clasificar imágenes** y decirte **a qué videojuego pertenece** una imagen específica.

## 🎯 Objetivo

Identificar correctamente el juego al que corresponde una imagen subida por el usuario. Ideal para coleccionistas, fanáticos o como herramienta de reconocimiento visual en entornos automatizados.

## 🧠 Modelo

- **Framework:** TensorFlow + Keras
- **Modelo:** Red neuronal convolucional (CNN)
- **Entrenamiento:** Dataset personalizado con capturas de pantalla de distintos videojuegos (por ejemplo: Mario, Sonic, Zelda, Minecraft, etc.)
- **Entradas:** Imágenes en formato `.jpg` o `.png`
- **Salidas:** Etiqueta del videojuego correspondiente

## 🖼️ Ejemplo de uso

```python
# Cargar imagen y predecir
from predictor import predict_image

resultado = predict_image("ejemplo_mario.jpg")
print("Este juego es:", resultado)

