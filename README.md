# CRUD ejemplo MVT

Este codigo contiene:
 - Vistas 
 - Formularios
 - Modelos
 - Templates

**importnante: Este ejemplo fue probado con python 3.8.13 y Django 4.0.4**

## Checkear que tengas Python

Para comenzar primero tienen que asegurarse que tienen instalado, python.

En windows tiene que abrir una terminal cmd o powershell.

```PS
PS C:\> python --version
Python 3.X.X 
```

En Linux/Mac tiene que abrir una terminal bash

```bash
$ python --version
Python 3.X.X 
```

Si la version corresponde a la misma o es superior, se puede correr sin inconvenientes. De lo contrario se debe de descargar una version nueva de python desde este [link](https://www.python.org/downloads/).

## Instalar django

En una terminal cmd o powershell desde windows:

```PS
C:\> pip install django
```

Linux/Mac:

```bash
$ pip install django
```

Si no arrojo errores esto es suficiente para poder correr el projecto.


# Instalar django bootstrap v5

```PS
C:\> pip install django-bootstrap-v5
```

Linux/Mac:

```bash
$ pip install django-bootstrap-v5
```
## Clonar el projecto con git

windows:

```PS
C:\> git clone https://github.com/RaffaPH/mi-primer-mvt-main.git
```

Linux/Mac:
```bash
$ git clone https://github.com/RaffaPH/mi-primer-mvt-main.git
```

## Correr el Servidor

Los siguinetes comandos son analogos en Mac/Linux/Windows:

```bash
cd mi-primer-mvt
python manage.py migrate
```
La consola mostrara las migraciones de la base de datos que se realizaron.

Luego arrancamos el servidor web

```bash
python manage.py runserver
```
Listo ya tenes corriendo el ejemplo.

ahora Hace click en el siguiente link para ver el ejemplo corriendo: 

[http://localhost:8000/](http://localhost:8000/)

