# WhisperX - Google Colab
Guía de como ejecutar WhisperX en google colab

Este Jupyter Notebook contiene una guía para poder ejecutar el Modelo de WhisperX en Google colab, para luego crear una API desde Google colab utilizando FastAPI, para luego crear un tunel con ngrok para exponer esta API de manera publica.

Requisitos:
- Python 3.10 o superior
- Cuda 12.1
- Torch 2.5.1+cu121
- ffmpeg
- cuDNN - libcudnn8

Para ejecutarlo en un computador de manera local (no en google colab) es necesario tener instaldo ffmpeg y lo más importante CUDA v12.1 que es la versión que he encontrado que funciona correctamente con las dependencias de WhisperX. Para ello es necesario tener instalado libcudnn8, que se obtiene descargando cuDNN, desde https://developer.nvidia.com/rdp/cudnn-archive y descargar alguna versión que sea válida para CUDA 12.1 y que corresponda con el sistema operativo donde se va a ejecutar.
