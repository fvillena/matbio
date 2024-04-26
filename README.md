[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fvillena/matbio/master)

# Matemáticas para la Bioestadística

_Fabián Villena, MSc_

En este repositorio cargaremos todos los recursos necesarios para la unidad de programación en `R` del curso. Este repositorio incluye en la carpeta `data` una muestra de la base de datos `MIMIC-III`, la cual será la base para los análisis realizados en este curso.

## Preparación del ambiente de desarrollo

Video de la clase: https://www.youtube.com/watch?v=fJR4FtsyTGQ

Para la correcta reproductibilidad de los códigos que desarrollemos utilizaremos la herramienta `Git` para controlar los cambios que surjan a través del curso y además utilizaremos `Anaconda` como gestor de paquetes para establecer el ambiente de trabajo.

### 1. Instalación de Git y clonación del repositorio

* Descargar `Git` desde su página oficial: https://git-scm.com/downloads
* Para los usuarios de Mac preferir la opción "homebrew" y ejecutar el comando en la aplicación Terminal (consola).
* Para usuarios de Windows, ejecutar el instalador y seguir las instrucciones. Luego ejecutar `Git Bash`.
* Para Linux, hay una variedad de opciones dependiendo de la distribución que tiene. Puede contactar al equipo docente en caso de dudas. 
* Escribir el comando `git clone https://github.com/fvillena/matbio.git` y ejecutarlo en esa consola.

Al seguir estos pasos, se habrá creado una carpeta llamada `matbio` con todos los elementos necesarios para desarrolar el curso. Al avanzar en el curso iremos actualizando los códigos, por lo que será necesario que ejecuten periodicamente `git pull` para actualizar su copia local del repositorio con los últimos cambios.

### 2. Instalación de Anaconda e inicialización del ambiente

* Descargar `Anaconda` desde su página oficial: https://www.anaconda.com/products/individual
* Ejecutar el instalador y seguir las instrucciones.
* Ejecutar `Anaconda Prompt` (o `conda` si tiene macOS).
* Dirigirse a la carpeta del curso con `cd matbio`
* Ejecutar en la consola el comando `conda env create -f environment.yml --force`.
* Ejecutar `conda activate matbio`.
* Inicializar el entorno conda usando `conda init`.
* Ejecutar el comando `jupyter notebook`.

Al seguir estos pasos habrán instalado todos los paquetes necesarios en el curso y se debe haber abierto una ventana de su navegador con la plataforma `Jupyter`, prueba crear un nuevo notebook y comienza a programar en `R`.

## Método alternativo

Si no deseas o no puedes instalar las herramientas antes mencionadas, puedes utilizar el servicio de Binder, el cual genera un contenedor virtual con todo lo lo necesario para llevar a cabo las clases. Debes tener en cuenta que todos los cambios que realices en este entorno son efímeros y desaparecerán cuando termines tu sesión. Esta opción es buena si no estás en tu computador y deseas practicar rápidamente. Para acceder al Binder del curso debes presionar el botón que se encuentra al principio de este README. Si se han hechos cambios recientes en este repositorio, debes esperar a que se regenere el contenedor y esto puede tardar unos minutos, cuando se haya regenerado el contenedor puedes volver a acceder rápidamente al mismo.
