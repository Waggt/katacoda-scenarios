# Trabajando con repositorio local #
Git es un sistema de control de versiones distribuido y nos permite tener una copia completa funcional de un repositorio en nuestra PC.

## Configurando usuario y correo electrónico ##
Previo a trabajar con git debemos configurar algunos valores globales, para que git tenga control de quien hace los cambios.

Configuremos el nombre de usuario y correo electrónico.

git config --global user.name "John Doe"
git config --global user.email "John Doe@email.com"

# Creando un repositorio Local #
Ademas de clonar un repositorio remoto, podemos también crear un repositorio local que luego podemos sincronizar con algún servidor  remoto.

En nuestro caso utilizaremos GitHub.

## Prerequisitos ##
1. Git CLI instalado
2. Usuario y correo electrónico configurados.

## Pasos ##
1. Creamos un directorio
 `mkdir hello-world`{{execute}}
2. Nos cambiamos al directorio creado
`cd hello-world`{{execute}}
3. Inicializamos el repositorio
`git init`{{execute}}
4. Se creará un directorio con el nombre ".git"
`ls -l .git`{{execute}}

Ahora que tenemos creado el directorio git podemos iniciar a trabajar con archivos y directorios de nuestro repositorio.

No se necesita estar conectado al servidor remoto para poder trabajar con el repositorio local.
