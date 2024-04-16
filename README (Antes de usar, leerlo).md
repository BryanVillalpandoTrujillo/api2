Funcionamiento De la API.
(Probar en visual studio).

Es necesario modificar en las carpeta properties el archivo  ServiceDependence.json y en models el appsettings.Development.json
                          Server= Al Valor de tu ip (local) para que actue como servidor.

Puerto= Generalmente el de escucha de sqlserver es el 1433, sin embargo para el uso con docker lo cambié a 14033.

Puerto local sin docker= En caso de tener problemas al ejecutar el docker, se puede restaurar el archivo Licenciaturas.bak
Este archivo, es una copia de las carreras, y cambiar la ip(Propia) y el puerto a usar (1433).

El fin de esta práctica es familiraznos con el entorno de docker, la creación de imagenes y repasar conceptos de API (Peticiones).
