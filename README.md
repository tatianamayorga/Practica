# Practica
Proyecto de practica de pull request, crear el "FORK"

PULL REQUEST
git clone <link del repo>

entrar a la carpeta
cd <name>

creamos una rama, de forma local en nuestra computadora
git checkout -b <Fix-Readme> 

git status
git diff

//Realizar modificaciones
git status
git commit -m "comentarios"

listado de ramas
git branch

GIT PUSH, subir al repositorio clonado en git hub
git push origin <name de rama creada>

//Hacer el comentario de pull request
*OTROS COMANDOS*

//another comentarios- 
ELIMINAR ARCHIVO
git rm <name.file>

RESTAURAR ARCHIVO
git restore <name.file>

CAMBIAR DE NOMBRE ARCHIVO
git mv <nombre_original> <nombre_nuevo>

CAMBIAR DE RAMA
git switch <name-rama>

FUSIONAR RAMA CON LA RAMA PRINCIPAL
git merge -m "Fusionar rama Fix-Readme con rama principal" <name.rama_Fix-Readme>

ELIMINAR RAMA
git branch -d <name.rama>  

CAMBIA DE RAMA Y CREA UNA NUEVA RAMA
git switch -c <name.rama.new>

-REALIZA CAMBIOS EN AMBAS RAMAS
-GUARDALOS
-INTENTA FUSIONARLAS. SE CREA UN CONFLICTO
-INGRESA AL ARCHIVO
	HEAD, se refiere a cual es la realidad actual o lo que hay actualmente
	Abajo esta el texto que se intent cambiar de la rama segundaria a la rama principal. Borrar lo que esta en HEAD. Para conservar lo de abajo.

*conservar*
Pruebas 