# Comparación de Frameworks de Deep Learning: JAX, PyTorch y TensorFlow

Este proyecto realiza una comparación entre tres populares frameworks de deep learning: **JAX**, **PyTorch** y **TensorFlow**, utilizando el conjunto de datos CIFAR-10. El objetivo principal es comparar el rendimiento y la velocidad de entrenamiento de estos frameworks en una tarea de clasificación de imágenes.

## Descripción

El código entrena un modelo CNN (Convolutional Neural Network) básico en JAX, PyTorch y TensorFlow utilizando el conjunto de datos CIFAR-10. Durante el entrenamiento, se mide el tiempo de ejecución y la pérdida en cada iteración. Posteriormente, se comparan los resultados en un gráfico que muestra la evolución de la pérdida a lo largo del entrenamiento en cada framework.

### Los siguientes pasos se realizan en el proyecto:
1. **Carga del dataset CIFAR-10**: Este es un dataset estándar en visión por computadora que contiene 60,000 imágenes de 10 clases diferentes.
2. **Definición del modelo CNN** en JAX, PyTorch y TensorFlow.
3. **Entrenamiento** de los modelos con una época para cada framework.
4. **Medición del tiempo de entrenamiento** en cada uno de los frameworks.
5. **Visualización** de las pérdidas durante el entrenamiento para cada framework en un solo gráfico.

## Requisitos

Para ejecutar este proyecto, necesitas tener instaladas las siguientes bibliotecas en tu entorno Python:

- `jax`
- `jaxlib`
- `torch`
- `tensorflow`
- `flax`
- `matplotlib`
- `torchvision`
- `optax`

Puedes instalar estas dependencias usando `pip`:

```bash
pip install jax jaxlib torch tensorflow flax matplotlib torchvision optax
