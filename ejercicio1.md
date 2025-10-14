# Documentación Ejercicio 14

## Paso 1
![Captura1](/imagen1.png)

Creamos el repositorio dentro de la carpeta de Repositorios y lo inicializamos con git init y aprovecharemos a conectar el repositorio local al remoto con el primer comando indicado en la captura, dentro del repositorio creamos dos archivos de texto. Siempre hay que acordarse de confirmar los cambios con el proceso de siempre, git add ., git commit -m "Texto" y git push para subir los cambios al repositorio en Github. (Todo esto desde el Git Bash de la maquina local)

## Paso 2 
![Captura2](/imagen2.png)

Ahora desde la maquina cliente de Debian, debemos clonar el repositorio creado en local a la maquina cliente, para ello usamos el comando indicado en la captura de pantalla (git clone), necesitaremos la URL del repositorio de Github, el Token y el nombre de Usuario. Después de este proceso deberiamos de tener el mismo repositorio de la maquina local en la cliente de Debian, donde apareceran los dos archivos de textos creados anteriormente.

## Paso 3
![Captura3](/imagen3.png)

Ahora volviendo a la maquina local, modificaremos un archivo de los dos creados anteriormente y crearemos uno nuevo llamado archivo3.txt. Ahora repetiremos los pasos para confimar los cambios y subirlos al repositorio de GitHub (comandos indicados en la captura de pantalla, son los mismos que en el paso 1).

## Paso 4
![Captura4](/imagen4.png)

Este es el contenido del archivo1.txt que he modificado

## Paso 5
![Captura5](/imagen5.png)

Ahora actualizaremos los cambios en el debian, bajando los cambios del repositorio de GitHub usando git pull. Después de de esto deberiamos de ver los cambios realizados en el local, es decir, el archivo1.txt deberia de estar modificado y el archivo3.txt deberia de aparecer. Comprobamos con un ls y un nano archivo1.txt.