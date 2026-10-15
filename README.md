# Perceptrón Multicapas

_Autor: Mauricio Montes_

Este repositorio contiene de una forma sintetizada la investigación realizada para la Jornada de Conferencias del Día de Pi organizada por el Departamento de Matemáticas de la Universidad Centroamericana José Simeón Cañas.

Dentro de la carpeta de apuntes hay PDFs con los temas que investigué, tratando de encontrarles sentido al principio y luego viendo lo asombroso y elegante de la estructuración de las redes neuronales.

También está el Pipeline para convertir los datos del MNIST para convertirlos en vectores numéricos para que el perceptrón los pueda recibir; y el notebook `perceptron.ipynb` que contiene el razonamiento de lo que se hizo para contruir a la red neuronal.

Recomiendo utilizar un entorno virtual para correr el notebook, los paquetes requeridos se encuentran todos en el archivo `requirements.txt`. Supongo que con Anaconda sale fácil, pero por mi parte, prefiero correr el siguiente comando dentro del repositorio:

```bash
$- python -m venv .venv
```

Y luego, para activarlo:

```bash
$- source .venv/bin/activate
```

Una vez activo el entorno virtual, solo queda instalar las dependencias.

```
$- pip install -r requirements.txt
```