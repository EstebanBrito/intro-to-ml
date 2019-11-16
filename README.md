# Introducción al Machine Learning
Repositorio del taller "Introducción al Machine Learning" impartido durante el Dev Day AI Mérida 2019.   
Tallerista: Esteban E. Brito Borges.   
Correo: esteban.brito.borges@gmail.com

# ¿Cómo usar este repositorio?

## Especificaciones

Este proyecto fue hecho en un sistema operativo Linux, usando Python 3.6.
Librerías utilizadas:
* jupyter
* numpy
* pandas
* matplotlib
* scikit-learn

## Descargar el repo

Clona el repositorio o descárgalo de GitHub (https://github.com/EstebanBrito/intro-to-ml)

```bash
$ git clone <URL-del-repo>
```

## Utilerías del sistema.

Si ya tienes instalado pip y virtualenv, salta a la sección "Preparando el entorno"

Instala la herramienta pip (gestor de paquetes de Python). Visita https://linuxize.com/post/how-to-install-pip-on-ubuntu-18.04/ para más información.

```bash
$ sudo apt update
$ sudo apt install python3-pip
```

Si python-pip genera error, instala otra version

```bash
$ sudo apt install python-pip
```

Dependiendo de cuál versión de pip instalaste, usa "pip3" o "pip" en las siguientes instrucciones.

## Preparando el entorno

Instala las librerías

```bash
$ python3 -m pip3 install -r requirements.txt
```

En caso de fallo, instala las librerías de forma manual

```bash
$ python3 -m pip3 install jupyter numpy pandas matplotlib scikit-learn
```

Activa el servidor de Jupyter (para acceder a las notas del talleres)

```bash
$ (jupyter notebook
```

Se abrirá un navegador. Si no sucede, toma la URL que se muestra en consola y accede a ella manualmente en el navegador.
El navegador mostrará un directorio de archivos, desde el que podrás consultar las notas (en ML/Regression.ipynb)