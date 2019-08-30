# Una introducción al aprendizaje profundo multitarea

Este repositorio contiene los materiales del taller presentado en la [RIIAA 2019](https://riiaa.org).

* Aprendizaje profundo.
  * Aprendizaje supervisado.
  * Esquemas de aprendizaje y modelos.
  * Perceptrón multicapa.
  * Redes convolucionales.
  

* Aprendizaje multitarea.
  * Aprendiendo de más fuentes.
  * Aplicaciones.
  * Esquemas de aprendizaje y modelos.
  * Problemas abiertos.


## Configuración del ambiente

Los ejemplos del taller se pueden seguir usando:
 * Google Colab: recomendado para aquellos poco familiarizados programación y el entorno Python en general.
 * Conda/virtualenv: para aquellos que deseen crear un ambiente para correr los ejemplos en su equipo.

### Google Colab

Google Colab es un servicio gratuito que permite ejecutar libretas de Jupyter que se encuentren almacenadas en una cuenta de Google Drive. Usarlo para este taller es sencillo. Habiendo entrado previamente a tu cuenta de Drive, abre al libreta `1_mlp.ipynb` dentro del directorio `notebooks` y presiona sobre el icono: 

![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)

esto importará la libreta en tu Drive. Ahora, en el menu "Runtime -> Change runtime type" seleccionamos Python 3 y GPU, y guardamos. Finalmente corremos la libreta en "Runtime -> Run all".

### Conda/virtualenv

Para usar esta opción primero necesitamos crear un entorno virtual de Python 3.6 usando conda o virtualenv y después instalar las dependiencias en el archivo `requirements.txt`.

Ahora con entorno activo, entramos el repositorio clonado y ejecutamos Jupyter:

```shell
$ jupyter notebook
```
