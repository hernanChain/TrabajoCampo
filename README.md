# Proyecto ***PRODULECT***
La aplicación fue desarrollada en el lenguaje de programación ***python*** y usando el framework ***Django***.

El grupo ***SMARTSOFT***  :computer: está conformado por:

* Cristian Andres Arias Páez [GitHub :pencil2:](https://github.com/AriasPaez/)  
* ![descarga (1)](https://user-images.githubusercontent.com/58449699/74971387-02a65b00-53ee-11ea-949e-318dd77a4f66.png) Hernan Alirio Cadena Gonzalez [Github](https://github.com/hernanChain/) ![github-logo](https://user-images.githubusercontent.com/58449699/74889717-dd630f80-534f-11ea-855c-a117c0a2f547.png)
* Liseth Juliana Péres Mesa
* Lina María Ramírez Martínez
* Joham Sebastian Medina Corredor [GitHub Joham](https://github.com/JohamSMC/)

## :one: Pasos para instalar la aplicación Web :page_facing_up:

* Primer paso:
> Se sugiere crear un entorno virtual, para lo cual se debe tener instalado ***python*** y el gestor de paquetes ***PIP***

* Segundo paso:
> Instalar **virtualenv**

```
python -m pip install virtualenv
```

* Tercer paso:
> Despues procedemos a crear un entorno virutal

```
python -m venv nombreEntornoVirtual
```

* Cuarto paso:
> Despues de crear el entorno virtual, inicializamos el entorno virtual, para esto nos ubicamos
> en la ruta 

 ``../nombreEntornoVirtual/Scripts/``

>y ejecutamos la siguiente linea:

```
activate
```

* Quinto paso:
> Nos ubicamos en la carpeta donde descargarmos el proyecto y verificamos que existe el archivo
***``requirements.txt``***

> y ejecutamos el comando:

```
pip install -r requirements.txt
```

> Con este comando se instalara todas las librerias necesarias para el proyecto.

* Sexto paso:
> Despues procedemos a inicializar el proyecto("Estando Ubicados en la raiz del proyecto"):

```
python manage.py runserver
```

## :two: Testing
> Por consola, ubicado en la raíz del proyecto (donde está ubicado el archivo ***manage.py***, dentro de la carpeta PRODULEC):

```
python manage.py test produlect
```


