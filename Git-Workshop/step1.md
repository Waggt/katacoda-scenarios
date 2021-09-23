## Clonar un repositorio remoto #
Git nos permite clonar un repositorio existente ejecutando la siguiente instrucción:

git clone [URL]

## Creando un repositorio Local##
Podemos también crear un repositorio local que luego podemos sincronizar con un repositorio remoto.

1. Creamos un directorio
 `mkdir hello-world`{{execute}}
2. Nos cambiamos al directorio creado
`cd hello-world`{{execute}}
3. Inicializamos el repositorio
`git init`{{execute}}
4. Se creará un directorio con el nombre ".git"
`ls -l .git`{{execute}}
