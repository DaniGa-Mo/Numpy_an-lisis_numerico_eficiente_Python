🧮 Curso NumPy: Análisis Numérico Eficiente

Este repositorio contiene mis prácticas y ejercicios realizados tras completar el curso “NumPy: análisis numérico eficiente con Python”.

📚 Lo aprendido

✔ Generación de secuencias y números aleatorios.

✔ Uso de np.random.seed() para reproducibilidad.

✔ Manipulación y agrupación de arrays.

✔ Guardado y carga de datos con np.save, np.load y np.savetxt.

🚀 Tecnologías

Python 3

NumPy

🧪 Ejemplo básico

```python
import numpy as np

np.random.seed(42)
arr = np.random.rand(5)

np.save("array.npy", arr)
cargado = np.load("array.npy")

```


🎯 Objetivo

Registrar y compartir mi progreso en NumPy para futuros proyectos de análisis de datos.
