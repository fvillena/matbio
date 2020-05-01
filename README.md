# Matemáticas para la Bioestadística

_Fabián Villena, MSc_

_Jocelyn Dunstan, PhD_

En este repositorio cargaremos todos los recursos necesarios para la unidad de programación en `R` del curso. Este repositorio incluye en la carpeta `data` una muestra de la base de datos `MIMIC-III`, la cual será la base para los análisis realizados en este curso.

## Preparación del ambiente de desarrollo

Para la correcta reproductibilidad de los códigos que desarrollemos utilizaremos la herramienta `Git` para controlar los cambios que surjan a través del curso y además utilizaremos `Anaconda` como gestor de paquetes para establecer el ambiente de trabajo.

### 1. Instalación de Git y clonación del repositorio

* Descargar `Git` desde su página oficial: https://git-scm.com/downloads
* Ejecutar el instalador y seguir las instrucciones.
* Ejecutar `Git Bash`.
* Escribir el comando `git clone https://github.com/fvillena/matbio.git` y ejecutarlo en esa consola.

Al seguir estos pasos, se habrá creado una carpeta llamada `matbio` con todos los elementos necesarios para desarrolar el curso. Al avanzar en el curso iremos actualizando los códigos, por lo que será necesario que ejecuten periodicamente `git pull` para actualizar su copia local del repositorio con los últimos cambios.

### 2. Instalación de Anaconda e inicialización del ambiente

* Descargar `Anaconda` desde su página oficial: https://git-scm.com/downloads
* Ejecutar el instalador y seguir las instrucciones.
* Ejecutar `Anaconda Prompt`.
* Dirigirse a la carpeta del curso con `cd matbio`
* Escribir el comando `conda env create -f environment.yml --force` y ejecutarlo en esa consola.
* Escribir el comando `conda activate matbio` y ejecutarlo en esa consola.
* Escribir el comando `jupyter notebook` y ejecutarlo en esa consola.

Al seguir estos pasos habrán instalado todos los paquetes necesarios en el curso y se debe haber abierto una ventana de su navegador con la plataforma `Jupyter`, prueba crear un nuevo notebook y comienza a programar en `R`.