# Curso: "Acceso a Información Relevante  en la Era de los Datos Masivos - Versión 2" (UNPA UACO - Escuela de Informática 2024)
Repo del Curso **"Acceso a Información Relevante  en la Era de los Datos Masivos - Versión 2"** de la Escuela de Informática de UNPA UACO, 2024 

Este repositorio contiene notebooks Python con ejemplos y ejercicios que cubren cada una de las clases.


## Introducción

Este curso presenta algunas de las técnicas actuales detrás de las aplicaciones de búsqueda de escala web que se utilizan diariamente (considerando tanto eficacia como eficiencia). 
Se abordan temas de procesamiento de textos usando tecnologías del lenguaje. Se propone un enfoque práctico donde cada día se prueben en código algunas de las ideas presentadas. 
Las clases están divididas en cuatro temas:


- Presentación [[Diapos]]()
- Día 1: Indexación y Recuperación [[Diapos]]()
- Día 2: Compresión [[Diapos]]()
- Día 3: Caching [[Diapos]]()
- Día 4: Representaciones Densas y Recuparación [[Diapos]]()
- Día 5: Aplicaciones [[Diapos]]()
- Cierre [[Diapos]]()

## Setup
Clonar este repo:
```
$ git clone https://github.com/tolosoft/UNPAEI2024_AIREDMv2.git
```
Ejecutar la siguiente imagen de Docker (la primera vez se descarga de [Docker Hub](https://hub.docker.com/repository/docker/tolosoft/cacic_airedm/general)):

```
$ docker run -p 8888:8888 -e GRANT_SUDO=yes --user 1001:100 -w /home/jovyan -v "/home/alumno:/home/jovyan/" tolosoft/cacic_airedm:latest
```

La misma está basada en jupyter/base-notebook (https://hub.docker.com/r/jupyter/base-notebook) y contiene todas la librerías necesarias para ejecutar los ejemplos del curso.
Para reconstruir la imagen desde cero, editar y usar el Dockerfile que se encuentra en ./docker


