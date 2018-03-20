<img src="https://i.imgur.com/TkbiSQY.png" width="175" align="right">

# Linkedin Learning Downloader
[![built with Requests](https://img.shields.io/badge/built%20with-Requests-yellow.svg?style=flat-square)](http://docs.python-requests.org)
[![built with Python2.7](https://img.shields.io/badge/built%20with-Python2.7-red.svg?style=flat-square)](https://www.python.org/)

### Una pequeña herramienta que descarga los cursos de Linkedin Learning
Implementado en python usando requests

### Modo de uso
Primero instala los requerimientos:
```
pip install -r requirements.txt
```
En el archivo `config.py`, escribe tus datos de inicio de sesión, la ruta de descarga y llena la ficha de `COURSES` con el registro de los cursos que deseas descargar, por ejemplo:

`https://www.linkedin.com/learning/fundamentos-esenciales-de-la-programacion/ -> fundamentos-esenciales-de-la-programacion`

```
USERNAME = 'user@email.com'
PASSWORD = 'password'
BASE_DOWNLOAD_PATH = 'E:/Downloads/LinkedInLearning' #usa "/" como separador

COURSES = [
    'fundamentos-esenciales-de-la-programacion',
    'premiere-pro-cc-2017-esencial'
]
```
Luego ejecuta el script:
```
python lld.py
```
Los cursos se guardarán en la carpeta de descargas que hayas definido.

### Demo (Desactualizado por ahora)
[![asciicast](https://asciinema.org/a/143894.png)](https://asciinema.org/a/143894)

---
###### Que los disfrutes y sientete libre de reportar cualquier problema.
---
