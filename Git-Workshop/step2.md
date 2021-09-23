##Agregando un archivo a nuestro repositorio##

1. Creamos el archivo por ejemplo:
`echo "Mi primer Repositorio" >>README.MD`{{execute}} podemos utilizar cualquier editor para crear el archivo por ejemplo `/hello-world/README.MD`{{open}}
2. Agregamos el archivo al repositorio, todos los archivos a los que le queremos dar seguimiento tienen que ser agregados:
`git add README.MD`{{execute}}
3. Para comprometer los cambios utilizamos:
`git commit -m "Mi primer cambio confirmado"`{{execute}}
4. En cualquier momento podemos comprobar el estado de nuestro trabajo con:
`git satus`{{execute}}