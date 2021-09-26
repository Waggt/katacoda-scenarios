## Agregando archivos a nuestro repositorio ##

Ahora que estamos listos para agregar archivos, agregaremos algunos de ellos.

## Pasos ##
1. Creamos el archivo README.MD:
`echo "Mi primer Repositorio" >>README.MD`{{execute}} podemos utilizar cualquier editor para crear el archivo por ejemplo `/hello-world/README.MD`{{open}}.
`vi /hello-world/README.MD`{{open}} para editarlo con vi.
`git status`{{execute}} para ver el estado actual del repositorio.

2. Creamos el archivo **.gitignore** con el editor de nuestra preferencia, dentro de este archivo agregaremos el listado de archivos que no queremos agregar a nuestro repositorio, por ejemplo archivos compilados, backups, etc.
`git status`{{execute}} para ver el estado actual del repositorio.

3. Agregamos los archivos al stage area.
`git add README.MD`{{execute}} 
`git add .gitignore`{{execute}}

Otras opciones son:
a. `git add .`{{execute}} Agrega el directorio actual.
b. `git add --all`{{execute}} Agrega archivos nuevos, modificados o eliminados al stage area.

Los archivos agregados al stage area son los que serán actualizados en el repositorio en el siguiente commit.

4. Para enviar los cambios del stage area al repositorio utilizamos **git commit -m [comentario]**:
`git commit -m "Mi primer cambio confirmado"`{{execute}}

5. En cualquier momento podemos comprobar el estado de nuestro trabajo con:
`git satus`{{execute}}


### Ejercicio Práctico ###
1. Crea un archivo llamado 'app.js'
2. Crea un archivo llamado 'package.json'
3. Modifica el archivo con las siguientes instrucciones.

   *app.js*
   ```javascript
    console.log('hola mundo');
    ```
   *package.json*
   ```javascript
    {}
   ```
4. Agrega los archivos al repositorio con add
5. Actualiza los cambios en el repositorio con commit.