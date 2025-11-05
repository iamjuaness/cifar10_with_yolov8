# 🚀 Clasificación de Imágenes con YOLOv8 y CIFAR-10

Un proyecto práctico y didáctico para entrenar modelos de **clasificación de imágenes** usando YOLOv8 (Ultralytics) y el dataset CIFAR-10, todo en Jupyter Notebook / Google Colab.

## 🧰 Características

- 📦 **Descarga y organización** del dataset CIFAR-10 adaptado para YOLO.
- 🧠 **Entrenamiento** de un modelo YOLOv8 pre-entrenado (nano, clasificación).
- 🖼️ **Visualización interactiva** de imágenes y predicciones.
- 📊 **Evaluación** completa: precisión `top-1` y `top-5`, métricas automáticas.
- 📝 **Exportación** del modelo entrenado a ONNX para producción.
- 📈 **Gráficas y matriz de confusión** para análisis visual.

---

## 🗂️ Estructura del Proyecto

```bash
cifar10_with_yolov8/
├── data/
│ └── cifar-10-batches-py/
│ └── cifar-10-python.tar.gz
├── dataset/
│ └── train/
│ └── val/
├── runs/
│ └── classify/
│ └── train/
├── notebook.ipynb
├── yolov8n-cls.pt
├── README.md
└── LICENSE
```

---

## 💻 Ejecución Rápida

> Ingresa a `notebook.ipynb`y ejecuta los pasos 1 a 9 en la sección `Primeros Pasos`.

---

## ⚡ Primeros Pasos

1. **Importa las librerías** necesarias.
2. **Estructura tu dataset** para YOLO: divide en `train` y `val`, por clase.
3. **Descarga y organiza CIFAR-10** automáticamente.
4. **Visualiza imágenes** para verificar la calidad de datos.
5. **Carga el modelo YOLOv8 nano (`yolov8n-cls.pt`)**.
6. **Entrena el modelo** con hiperparámetros ajustados para buen desempeño. (Si tienes el archivo `yolov8n-cls.pt` en la carpeta `cifar10_with_yolov8`, no es necesario entrenar el modelo nuevamente.)
7. **Evalúa** y consulta métricas `top-1` y `top-5`.
8. **Exporta a ONNX** para integración en otros sistemas.
9. **Visualiza gráficas** y la matriz de confusión.

---

## 📊 Ejemplo de Resultados

- Métricas y matriz de confusión:
![Resultados de Entrenamiento](runs/classify/train/results.png)
![Confusion Matrix](runs/classify/train/confusion_matrix_normalized.png)

---

## 🧐 Referencias

- [Ultralytics YOLO Docs](https://docs.ultralytics.com)
- [CIFAR-10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html)
- [YOLOv8 Quickstart](https://docs.ultralytics.com/quickstart/)

---

## ⚖️ Licencia

> Este proyecto es de uso educativo bajo licencia MIT.

---

**¿Te fue útil este repositorio? ¡Dale una ⭐ en GitHub y aporta con tu feedback!**