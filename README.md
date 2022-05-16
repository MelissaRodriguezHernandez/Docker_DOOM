# Ejecución de DOOM en Docker

[Link de las fuentes](https://github.com/GideonRed/dockerdoomd)

## Requisitos previos

-Tener instalado Docker

-Estar en un sistema operativo Linux

## Contenedores

Primero debemos bajarnos y descomprimir el siguiente archivo

[Link de descarga](https://web.archive.org/web/20160310005603if_/https://gideonred.com/bins/dockerdoomd.tar.gz)

```
tar xzvf dockerdoomd.tar.gz
```

Y a continuación ejecutaremos los siguientes comandos:

```
for i in {1..2} ; do docker run -d -t ubuntu:14.04; done
```
![primer comando](https://github.com/MelissaRodriguezHernandez/Docker_DOOM/blob/main/img/primer%20comando.png)

```
./dockerdoomd
```
![ejecucion contenedor](https://github.com/MelissaRodriguezHernandez/Docker_DOOM/blob/main/img/segundo%20comando.png)

## Conexión

Ahora con los contenedores iniciados procederemos a conectarnos por un VNC Viewer al juego, en mi caso utilizaré el programa Remmina que viene por defecto en mi sistema Linux.
El puesto es 5900 y la contraseña es 1234. 

![imagen juego](https://github.com/MelissaRodriguezHernandez/Docker_DOOM/blob/main/img/juego.jpeg)
