# Generador de Dígitos Sintéticos con GANs 🧠🤖

Este proyecto implementa una **Red Generativa Adversaria (GAN)** capaz de crear imágenes realistas de dígitos manuscritos (similares al dataset MNIST) que no existen en la realidad. El objetivo es generar datos sintéticos para entrenar sistemas de reconocimiento óptico (OCR) sin comprometer la privacidad de datos reales.

## 👥 Autores
* **Jorge Cataño**
* **Héctor López**

---

## 🚀 Manual de Instalación

Para ejecutar este proyecto en tu entorno local o en la nube, sigue estos pasos:

### Opción A: Ejecución rápida en Google Colab (Recomendado)
Simplemente abre el archivo `.ipynb` de este repositorio y haz clic en el botón "Open in Colab". Asegúrate de cambiar el entorno de ejecución a **T4 GPU**.

### Opción B: Instalación Local
1. Clona este repositorio:
   ```bash
   git clone [https://github.com/TU_USUARIO/Generador-Numeros-GAN.git](https://github.com/jorg3328/Generador-Numeros-GAN.git)
   
2. Instala las dependencias necesarias:
pip install -r requirements.txt

📖 Guía de Usuario
1. Entrenamiento del Modelo
El notebook incluye el código completo para entrenar la GAN desde cero.

Entrada: Ruido aleatorio (Vector de dimensión 100).

Salida: Imágenes de 28x28 píxeles en escala de grises.

Hiperparámetros: Puedes ajustar n_epochs (recomendado: 50) y lr (learning rate: 0.0002).

2. Uso de la Interfaz Gráfica (App)
Al final del notebook, ejecutamos una interfaz construida con Gradio.

Ejecuta la última celda del código.

Se generará un enlace público (ej. gradio.live).

Controles:

Slider (Semilla): Desliza para cambiar la "semilla" aleatoria y generar un número nuevo.

Salida: Verás el número generado con un zoom de 10x para mejor visualización.

📊 Tecnologías Utilizadas
Python

PyTorch (Construcción de la Red Neuronal)

Gradio (Despliegue de la interfaz web)

Matplotlib (Visualización de datos)
