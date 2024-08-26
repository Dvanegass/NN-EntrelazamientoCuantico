Este proyecto fue la reproducción del trabajo de Koutny et al., el cual explora la aplicación de redes neuronales artificiales en la predicción de la concurrencia de estados cuánticos entrelazados a partir de datos incompletos. 

Koutny, Dominik, et al. “Deep Learning of Quantum Entanglement from Incomplete Measurements.” Science Advances, vol. 9, no. 29, July 2023. https://doi.org/10.1126/sciadv.add7131.

Nuestro trabajo se centró en reproducir, corroborar y adaptar esta investigación precedente a nuestras capacidades computacionales. 

Se desarrollaron dos modelos de redes neuronales: uno entrenado a partir de una cantidad específica de proyectores (“Measurement specific”) y otro que se entrena solo una vez, utilizando información de todos los proyectores (“Measurement independent”); si falta información de algún proyector, la red recibe ceros en su lugar.

Estos modelos se entrenaron para predecir la concurrencia de estados cuánticos utilizando matrices de densidad generadas a partir de matrices aleatorias. El entrenamiento se llevó a cabo aprovechando la potencia computacional de Kaggle, lo que permitió manejar eficientemente el alto volumen de datos y la complejidad computacional del proyecto. Sin embargo, debido a la falta de la potencia computacional requerida para la tarea, y los tiempos del curso, se decidió limitar el estudio al caso de estados entrelazados de 2 qubits.

Este proyecto fue realizado en conjunto con compañeros del curso "Introducción a la investigación teórica" de la Universidad Nacional de Colombia.