# 2º GSI – Bezmiliana
#  Persistencia en Docker
## 26 de octubre del 2026
## Samuel Rivas Fernández
![][portada]

## **Creación y uso de volúmenes**

## Primero creo los 2 volumenes

![][img/1.png]

## Compruebo que se han creado los volumenes

![][img/2.png]

## Ahora inicio el contenedor asociando los volumenes creados antes

![][img/3.png]

## Paro el contenedor contenedor, lo borro y luego borro el volumen que estaba asociada al contenedor

![][img/4.png]

## **Bind mount para compartir datos**

## Creo la carpeta de saludo donde crearé el index.html

![][img/5.png]

## Creo el index.html

![][img/6.png]

## Ahora creo los 2 contenedores compartiendo la misma carpeta del equipo anfitrión

![][img/7.png]

## Muestro los contenedores activos

![][img/8.png]

## Y aquí están los servicios de ambos contenedores corriendo el mismo index

![][img/9.png]
![][img/10.png]
