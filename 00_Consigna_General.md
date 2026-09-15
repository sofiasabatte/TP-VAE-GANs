# TP: Autoencoders, VAE y GANs Convolucionales

## Organización

El TP está dividido en 3 notebooks, para hacer **en orden**:

1. `01_Autoencoder_Convolucional.ipynb`
2. `02_VAE_Convolucional.ipynb`
3. `03_GAN_Convolucional.ipynb`

Todas usan el dataset **CIFAR-10** y están pensadas para entrenarse en **Google Colab con GPU** (`Entorno de ejecución > Cambiar tipo de entorno de ejecución > GPU`) en un tiempo razonable (minutos, no horas).

Cada notebook tiene bloques marcados `# TODO` que hay que completar; el resto del código ya está resuelto.

## Modalidad de trabajo

- **Grupos de 2 personas.**
- Pueden **consultarse entre grupos** (discutir problemas, comparar resultados), pero cada grupo entrega su propio trabajo.

## Herramientas incluidas

- **TensorBoard**: para visualizar curvas de loss e imágenes generadas/reconstruidas durante el entrenamiento.
- **MLflow**: para trackear hiperparámetros, métricas y guardar los modelos entrenados como artifacts.
- **Optuna**: para hacer una búsqueda automática de hiperparámetros (notebooks 1 y 2).

## Entrega

Cada grupo entrega las 3 notebooks ejecutadas (con outputs visibles: gráficos, imágenes generadas, métricas), incluyendo:
- Los TODOs completados.
- Los hiperparámetros finales usados y por qué (según lo que haya encontrado Optuna, cuando aplique).
- Las preguntas de reflexión de cada notebook respondidas (pueden ser respuestas breves en celdas de markdown al final de cada notebook, o preparadas para responder oralmente).
- La sección grupal de la Notebook 3 (variante de GAN asignada) con su explicación y diagrama.

## Defensa oral

- **Duración: 40 minutos por grupo.**
- Formato conversado: se espera que comenten qué encontraron, qué decisiones tomaron (arquitectura, hiperparámetros), qué dificultades tuvieron y cómo las resolvieron.
- Deben poder explicar cualquier parte del código propio, no solo repetirlo.
- Cierre de la defensa: explicación de la variante de GAN que les tocó (asignada de forma reproducible en la Notebook 3 según el número de grupo), con diagrama simple del flujo (inputs → generador(es) → discriminador(es) → losses), diferencias respecto a la DCGAN de la notebook, y un caso de uso real.


Los tiempos pueden variar según la GPU asignada por Colab en ese momento.
