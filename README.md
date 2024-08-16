# Curso: "Acceso a Información Relevante  en la Era de los Datos Masivos - Versión 2" (UNPA UACO - Escuela de Informática 2024)
Repo del Curso **"Acceso a Información Relevante  en la Era de los Datos Masivos - Versión 2"** de la Escuela de Informática de UNPA UACO, 2024 

Este repositorio contiene notebooks Python con ejemplos y ejercicios que cubren cada una de las clases.


## Introducción

Este curso presenta algunas de las técnicas actuales detrás de las aplicaciones de búsqueda de escala web que se utilizan diariamente (considerando tanto eficacia como eficiencia). Se propone un enfoque práctico donde cada día se prueben en código algunas de las ideas presentadas. Las clases están divididas en cinco temas:


- Presentación [[Diapos]](https://docs.google.com/presentation/d/1PmNESuk9vGONW5ZA2jTEMD0hP_3vMTAUg663iHru65g/edit#slide=id.g24bd9a771fb_0_604)
- Día 1: Indexación y Recuperación [[Diapos]](https://docs.google.com/presentation/d/1mfWtzMN_0a1DTIGAs4F6zfGGQFiD5WkjepYTMECx_HA/edit?usp=drive_link)
- Día 2: Compresión [[Diapos]](#https://docs.google.com/presentation/d/1qFRyOdOYwM7DP0DgPoNZ6sxp6NBR3kH7Xdzdd07hCk0/edit#slide=id.gbcab2c191d_0_182)
- Día 3: Caching [[Diapos]](#https://docs.google.com/presentation/d/1JgqGI618nejYWOmo1smWds5RW6nt6PyR9nPuJ317U_8/edit)
- Día 4: Representaciones Densas y Recuparación [[Diapos]](#https://docs.google.com/presentation/d/1z33hYWVSqNd5GNyFO2l_QGy_hXUznQ8MtMaKthFZV7g/edit#slide=id.g24bd9a771fb_0_604)
- Día 5: Aplicaciones [[Diapos]](#https://docs.google.com/presentation/d/1fO9oSeizhWeG2xKeORCcMDrhj50jyGJi2hrWrQB3va4/edit#slide=id.g24bd9a771fb_0_604)
- Cierre [[Diapos]](#https://docs.google.com/presentation/d/1zuq8XEN9Qz3DrXqWDct3VJvyYV43HGyZlWjreXGtRxg/edit#slide=id.g2204e00caf1_0_2)

## Setup
Clonar este repo:
```
$ git clone https://github.com/tolosoft/UNPAEI2024_AIREDMv2.git
```
Ejecutar la siguiente imagen de Docker (la primera vez se descarga de [Docker Hub](https://hub.docker.com/repository/docker/tolosoft/cacic_airedm/general)):

```
$ docker run -p 8888:8888 -w /home/tolosoft -v "/home/tolosoft:/home/tolosoft" -it tolosoft/unpaei_airem2:latest
```

La misma está basada en jupyter/base-notebook (https://hub.docker.com/r/jupyter/base-notebook) y contiene todas la librerías necesarias para ejecutar los ejemplos del curso. 
Para reconstruir la imagen desde cero, editar y usar el Dockerfile que se encuentra en ./docker
