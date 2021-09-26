# Trabajando con Ramas - Primera parte #
Una rama es una copia de la rama principal en la cual podemos trabajar sin afectar la rama principal.

## Creando una Rama ##
Podemos crear una nueva rama con el comando **git branch[nombre_rama]**

## Pasos ##
1. Creamos la rama ** feature_task001 **
   `git branch feature_task001`{{execute}}
2. Confirmamos que la rama fue creada
   `git branch `{{execute}}
3. Ahora podemos cambiarnos a trabajar a la nueva rama
   `git checkout feature_task001`{{execute}}
4. Con nuestro editor favorito modificamos el archivo app.js
```javascript
   const express = require('express')
   const app = express()
   const port = 80

   app.get('/', (req, res) => {
   res.send('Hola mundo!')
   })

   app.listen(port, () => {
   console.log(`Escuchando en: http://localhost:${port}`)
  })
 ```
5. Vemos el estado del repositorio
`git satus`{{execute}}
6. agregamos el archivo app.js al stage area
`git add app.js`{{execute}}

