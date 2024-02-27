# Taller ML-CNN-HDIG

Taller introductorio de CNN para la Maestría de Humanidades Digitales en Uniandes, Bogotá D.C. 2021-10.

El trabajo consiste en entender cómo funciona tres redes neuronales basadas en convolución. La primera es un Autoencoder o una red para recrear conjuntos de datos. La segunda es un clasificador de prendas. Y la tercera, es un clasificador de prendas capas de remover ignorar errores (remover ruido).

Para el entrenamiento y optimización de los modelos se utiliza el conjunto MNIST de moda (FASHION MNIST DATA).

## Contenido

* **01-CNN-Autoencoder.ipynb:** Código interactivo para entrenar y probar un Autoencoder convolucional de 2 capas.
* **02-CNN-Classifier.ipynb:** Código interactivo para entrenar y probar un clasificador convolucional de 2 capas y 10 categorías de respuesta.
* **03-CNN-GAN.ipynb:** Código interactivo para entrenar y probar una red adversaria generativa (GAN) para crear imágenes de prendas de vestir.
* **04-CNN-Testbed.ipynb:** Código interactivo para probar los modelos entrenados y observar su comportamiento.

Los modelos entrenados NO cargan en el repositorio por el Gitignore.

## Datos

Los datos se pueden encontrar en la carpeta //Data o también en su fuente oficial [fashion-mnist](https://github.com/zalandoresearch/fashion-mnist)

En resumen, el conjunto posee 60.000 ejemplares y un conjunto de pruebas de 10.000 ejemplos. Cada ejemplo es una imagen en escala de grises de 28x28, asociada a una etiqueta de 10 clases.

Las etiquetas son:

| Label | Description |
| ----- | ----------- |
| 0     | T-shirt/top |
| 1     | Trouser     |
| 2     | Pullover    |
| 3     | Dress       |
| 4     | Coat        |
| 5     | Sandal      |
| 6     | Shirt       |
| 7     | Sneaker     |
| 8     | Bag         |
| 9     | Ankle boot  |

## Configuración

* **VS Code 1.56** como Ambiente de desarrollo (IDE).
* **Python 3.8** como lenguaje de programación principal.
* **Jupyter 1.0.0** como plataforma interactiva de desarrollo.
* **TensorFlow 2.4.1** para el entrenamiento y prueba de los modelos.
* **Keras 2.4.5** para el entrenamiento y pruebas de los modelos.
* **SKlearn 0.0.2** el preprocesamiento de los datos.
* **Pandas 1.2.3** para el preprocesamiento de los datos.

El código también puede ejecutarse en el IDE On-Cloud de [Google Colab](https://colab.research.google.com/notebooks/)

## Uso

Este es un taller de caracter introductorio que muestra el uso basico de las redes convolucionales o CNN como ejemplo y sustento de las explicaciones del taller de para el grupo de estudiantil de la ACM e IEEE Uniandino.
