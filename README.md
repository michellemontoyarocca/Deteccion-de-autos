# Detección de autos · comparación ReLU y Swish

Experimento de visión por computadora que compara funciones de activación ReLU y Swish en un modelo para imágenes de autos. El script `Comparación REFLU y SWISH.py` usa TensorFlow/Keras, OpenCV y utilidades de Google Colab.

Para reproducirlo se necesitan el dataset y las rutas que espera el script, un entorno compatible con TensorFlow y preferiblemente aceleración GPU. El repositorio actual no incluye el dataset ni un resultado empaquetado; por ello las cifras del experimento no pueden verificarse solo con este archivo.

Una comparación sólida debe mantener arquitectura, partición, semilla, épocas y presupuesto de cómputo iguales entre activaciones, y mostrar métricas por clase además de la precisión global. El nombre del archivo conserva la grafía original del experimento.
