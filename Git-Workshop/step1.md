# Clonar un repositorio remoto #
Git nos permite clonar un repositorio existente,  ejecutando la siguiente instrucción:

git clone [URL]
La URL tiene el siguiente formato:

 https://github.com/[__USUARIO__/[__REPOSITORIO__].git

Si el repositorio es público se creará un directorio llamado *REPOSITORIO* con el contenido del repositorio remoto.

Si el repositorio es privado, git solicitará algún mecanismo de authenticación.

Utilizaremos en este caso un Personal Access Token.

## Pre-requisitos##
1. Cuenta de GitHub
2. Repositorio *hola-mundo* creado con algunos archivos
3. Para repositorio privado, crear previamente el Token de acceso:
    a. GitHub/Settings/Developper settings/Personal access tokens/Generate new token.

## Pasos: ##
1. Desde GitHub copiar la URL del respositorio a clonar
2. Con el comando git clone, clonamos el repositorio.
 https://github.com/[__USUARIO__/hola-mundo.git