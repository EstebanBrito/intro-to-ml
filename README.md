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

## Preparar el entorno

Clona el repositorio o descárgalo de GitHub

```bash
$ git clone <URL-del-repo>
```

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

Instala la herramienta virtualenv (gestor de entornos virtuales de Python). Más información sobre virtualenv aquí: https://tecadmin.net/use-virtualenv-with-python3/

```bash
$ pip3 install virtualenv
```

Crea un entorno virtual (dentro de la carpeta del proyecto)

```bash
$ virtualenv -p python3 env
```

Activa el entorno

```bash
$ source env/bin/activate
```

Instala las librerías

```bash
$ (env) pip3 install -r requirements.txt
```

En caso de fallo, instala las librerías de forma manual

```bash
$ (env) pip3 install jupyter numpy pandas matplotlib scikit-learn
```

Activa el servidor de Jupyter (para acceder a las notas del talles)

```bash
$ (env) jupyter notebook
```

Se abrirá un navegador. Si no sucede, toma la URL que se muestra en consola y accede a ella manualmente en el navegador.
El navegador mostrará un directorio de archivos, desde el que podrás consultar las notas (en ML/Regression.ipynb)
