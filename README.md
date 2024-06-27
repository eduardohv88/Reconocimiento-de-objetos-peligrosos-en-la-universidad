# Reconocimiento de objetos peligrosos en la universidad

![image (1)](https://github.com/eduardohv88/Reconocimiento-de-objetos-peligrosos-en-la-universidad/assets/158246986/980e7210-f2cb-4e76-aac3-5d9989676128)

## Objetivo

El objetivo de este estudio es desarrollar e implementar un sistema basado en aprendizaje automático para la detección de objetos peligrosos en un campus universitario. Este sistema utilizará redes neuronales convolucionales pre entrenadas, ajustadas específicamente para identificar armas de fuego y armas blancas en imágenes captadas por cámaras de seguridad. Al integrar este sistema con la infraestructura de vigilancia existente en la universidad, se espera mejorar la capacidad de respuesta ante cualquier incidente, proporcionando un entorno más seguro para toda la comunidad universitaria.

## Uso de modelo preentrenado YoloV5s

YoloV5s (You Only Look Once version 5 small) es una versión ligera y eficiente del modelo YOLO para la detección de objetos en imágenes. Diseñado por Ultralytics, YoloV5s se caracteriza por su velocidad y precisión, haciéndolo adecuado para aplicaciones en tiempo real. Está construido sobre la arquitectura de YOLO, que divide las imágenes en una cuadrícula y predice las cajas delimitadoras y las probabilidades de clase simultáneamente.


![Imagen1](https://github.com/eduardohv88/Reconocimiento-de-objetos-peligrosos-en-la-universidad/assets/158246986/3eeea611-9b38-4da7-aed6-351b7d84f78f)

## Uso de dataset de armas y cuchillos

Se obtuvo el conjunto de datos llamado “Conjunto de datos de detección de armas para YOLOv5” de la página Kagle. El cual se puede acceder mediante el siguiente enlace: https://www.kaggle.com/datasets/raghavnanjappan/weapon-dataset-for-yolov5/data.

![dataset-cover](https://github.com/eduardohv88/Reconocimiento-de-objetos-peligrosos-en-la-universidad/assets/158246986/bad154b9-8e7d-421d-8aec-81de6eab764b)


## Resultados de entrenamiento


Para el entrenamiento del modelo se establecieron los siguientes parámetros por defecto:

- Tamaño de imágenes: 640x640
- Número de épocas: 30
- Tamaño del lote: 8
- Tasa de aprendizaje: 0.01
- Momentum: 0.937
- Decaimiento de peso: 0.0005


![image](https://github.com/eduardohv88/Reconocimiento-de-objetos-peligrosos-en-la-universidad/assets/158246986/a192609b-92c3-4bdc-89e4-b7ac5bead0ff)

## Graficas obtenidas

![descarga](https://github.com/eduardohv88/Reconocimiento-de-objetos-peligrosos-en-la-universidad/assets/158246986/7c09c8c6-37ad-46a9-837a-b2609beac5f9)
