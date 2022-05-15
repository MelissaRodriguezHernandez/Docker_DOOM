# Ejecución de DOOM en Docker

[Link de las fuentes](https://github.com/GideonRed/dockerdoomd)

## Requisitos previos

-Tener instalado Docker

-Estar en un sistema operativo Linux

## Pasos

Primero debemos bajarnos y descargar el siguiente archivo

[Link de descarga](https://web.archive.org/web/20160310005603if_/https://gideonred.com/bins/dockerdoomd.tar.gz)

Y a continuación ejecutaremos los siguientes comandos:

```
for i in {1..2} ; do docker run -d -t ubuntu:14.04; done
```
![primer comando]()

```
./dockerdoomd
```
![ejecucion contenedor]()

## Resultados

Si todo se ha ejecutado correctamente se abrira el juego DOOM totalmente funcional

![imagen juego]()
