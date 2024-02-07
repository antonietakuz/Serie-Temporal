# Serie-Temporal
Una serie temporal es un conjunto de muestras tomadas a intervalos de tiempo regulares. Es interesante analizar su comportamiento al mediano y largo plazo, intentando detectar patrones y poder hacer pronósticos de cómo será su comportamiento futuro. Lo que hace <<especial>> a una Time Series a diferencia de un “problema” de Regresión son dos cosas:

Es dependiente del Tiempo. Esto rompe con el requerimiento que tiene la regresión lineal de que sus observaciones sean independientes.
Suelen tener algún tipo de estacionalidad, ó de tendencias a crecer ó decrecer. Pensemos en cuánto más producto vende una heladería en sólo 4 meses al año que en el resto de estaciones.

## Table of Contents

- [Installation](#installation)


### Installation

Instalar anaconda o miniconda
https://www.anaconda.com/products/individual

a- Preparación del entornoGPU
$ conda create -n entornoGPU anaconda python=3.7.7
$ conda activate entornoGPU
$ conda install ipykernel
$ python -m ipykernel install --user --name entornoGPU --display-name "entornoGPU"
$ conda install tensorflow-gpu==2.1.0 cudatoolkit=10.1
$ pip install tensorflow==2.1.0
$ pip install jupyter
$ pip install keras==2.3.1
$ pip install numpy scipy Pillow cython matplotlib scikit-image opencv-python h5py imgaug IPython[all]

b-Preparación del entorno con Prophet
commands :
  step 1)  conda install libpython m2w64-toolchain -c msys2
  step 2) pip install prophet

execute this command in your Anaconda prompt /command prompt 
fbphophet is been renamed by prophet, so make sure you use prophet instead fbprophet.
