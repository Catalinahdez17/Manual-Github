## MANUAL DE GITBASH
# Descarga git para Windows
> Dentro del gitbash, se crea un repositorio nuevo con el siguiente comando:
> git init
>
Se crea una copia local del repositorio con:	
Git clone /path/to/manual
Git clone ckaritototo@hotmail.com/path/to/munual - si tiene un servidor remoto.
## flujo de trabajo de git:
Contiene tres “arboles” directorio de trabajo de tus archivos, Index de intermedio y HEAD la realización del ultimo commit.
# Para los cambios dentro del commit esta:
+ Git add <filename>
+ Git add
Para añadir al Index
+ Git commit –m “commit message”, permite ya estar incluido en el HEAD.
## ENVIO DE CAMBIOS
Para que los cambios queden en el repositorio el siguiente comando:
+ Git push origin master(como la ram)
Para conectar un repositorio que no había sido clonado y desea ser remoto, con la siguiente comando:
Git remote add origin <server>
## RAMAS
Durante el desarrollo  del repositorio, la rama vine por defecto y se puede hacerse cambio de rama.
Para cambio de rama:
+ Git checkout –b feature_x 
Volver a la rama principal es:
+ Git checkout master
Si se require borrar la anterior rama
+ Git branch –d feature_x
Teniendo la rama hecha, se necesita que quede en el repositorio para su uso.
+ Git push origin <branch>
Al actualizar el repositorio se necesita con el comando:
+ Git pull
Otra rama que se desee activar:
+ git merge <branch>
Al ener los cambios se necesita ser marcados como funcionados con:
+ git add <filename>
Revision:
Git diff <source_branch> >target_branch>
A la hora de publicar el repositorio,se recomienda etiquetar el commit
+ git tag 1.0.0 1v3b5u5ff, el u5ff refiere a los 0 caracteres de commit 
+ git log- para obtener uno
## REEMPLAZA CAMBIOS LOCALES

Por seguridad si algo sale mal, se puede reemplazar los cambios locales con:
+ git checkout -- <filename>
De manera inversa, si se requiere borrar los cambios locales y del commit se hace con el comando:
+ git fetch origin
+ git reset –hard origin/master
 ## DATOS A TENER EN CUENTA
Interface grafica
+ gitk
Para colres especailes 
+ git config color.ui true
Solo una línea para el commit 
+ git confif format.pretty online
Agregar archivos
+ git add .i


