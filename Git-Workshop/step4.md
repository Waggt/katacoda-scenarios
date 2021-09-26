# Configurando el repositorio remoto en GitHub #
Para sincronizar nuestro trabajo con GitHub ejecutamos los siguientes pasos:
1.  Renombramos la rama a main, para que coincida con la rama principal de GitHub.
`git branch -M main`{{execute}}
2. Agregamos el repositorio remoto con el nombre *origin*.
`git remote add origin https://github.com/[USUARIO]/helo-world.git`
3. Enviamos los cambios al repositorio remoto, la rama la rama main al repositorio remoto origin.
`git push -u origin main`{{execute}}

