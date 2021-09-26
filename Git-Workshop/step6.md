# Trabajando con Ramas - Segunda parte #
Cambiemos entre rama y rama para ver como git actualiza nuestros archivos dependiendo de la rama en la que estemos.

## Pre-Requisitos ##
1. Vamos a instalar algunos componentes necesarios para nuestra aplicación.
`npm install express`{{execute}}
2. Vamos a ejecutar la aplicación para comprobar los resultados
`node app.js`{{execute}}
3. Nuestra aplicación estará escuchando ahora en el puerto 80.
4. Comprobamos en el browser su funcionamiento.
5. Detenemos la aplicación con CTRL+C.

## Pasos ##

1. Nos cambiamos a la rama principal
 `git checkout master`{{execute}}
2. Vemos el contenido de app.js
  `cat app.js`{{execute}}
3. Ejecutamos la aplicación y comprobamos que es diferente a la rama *feature_task001*.
`node app.js`{{execute}}
4. Nos cambiamos nuevamente a la rama *feature_task001*
   `git checkout feature_task001`{{execute}}
5. Vemos el contenido de app.js
  `cat app.js`{{execute}}
6. Ejecutamos la aplicación y comprobamos que escucha en el puerto 80.
   `node app.js`{{execute}}

  
Hemos comprobado lo facil que es cambiarse entre ramas y la velocidad con que git actualiza los archivos.