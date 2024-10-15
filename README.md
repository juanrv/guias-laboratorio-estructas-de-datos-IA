# Introducción
 Guías de Laboratorio de estructuras de datos usadas en inteligencia artificial generativa, en este caso de la IA Stable Diffusion y en específico del componente del Autoencoder
# Instrucciones de uso
Para ejecutar la guía de laboratorio es necesario seguir los siguientes pasos para tener listo el entorno.
1.  Instalar [Anaconda Distribution](https://www.anaconda.com/download).
    * Para Linux usar las siguientes [intrucciones](https://docs.anaconda.com/anaconda/install/linux/).
2.  Instalar [PyTorch](https://pytorch.org/get-started/locally/).
3.  Instalar la librería de [FastCore](https://fastcore.fast.ai/): `conda install fastcore -c fastai`.
4.  Instalar [Hugginface Hub](https://huggingface.co/docs/huggingface_hub/installation): `conda install -c conda-forge huggingface_hub`.
5.  Instalar [Hugginface Datasets](https://huggingface.co/docs/datasets/installation): `conda install -c huggingface -c conda-forge datasets`.

    * En caso de no funcionar instalar con pip: `pip install datasets`.
6. Instalar [Fastprogress](https://github.com/fastai/fastprogress): `pip install fastprogress`.
7. Iniciar `Anaconda Navigator`
    * **Windows:** Anaconda instala automáticamente anaconda navigator, solo se debe ejecutar el acceso directo.
    * **Linux:** En una terminal luego de la instalación de anaconda usar el comando `anaconda-navigator`.
8. Iniciar **Jupyter Notebook** o **Jupyter Lab** y abrir el archivo `Guía laboratorio - CNN.ipynb`.

Debido a diferencias en sistemas operativos pueden surgir problemas con librerías faltantas, por este motivo es necesario prestar atención a los errores.
* Una de las librerías que puede dar problemas es PyArrow, en caso de ocurrir reinstalar la librería: `pip uninstall pyarrow` luego `pip install pyarrow`.
 
