# Practica 2 Victor Sanchez

## ¿Cómo se inicializa un repositorio en Git?
En Visual Studio Code tienes que abrir un archivo o carpeta y despues abrir la terminal de comandos con Ctrl+Ñ e introducir las siguientes lineas:
 ```
 git init
 git config --global user.name "Tu nombre" 
 git config --global user.email tucorreo@gmail.com
 ```
 Despues tienes que crear un repositorio en git, el mismo github te dira como hacerlo pero para agregar los avances a un repositorio existente:

 ```
 git remote add origin https://github.com/TuNombreDeUsuario/NombreDeTuRepo.git
 ```
 Despues tienes que indicar en que rama haras los cambios y hacer push: 
 ```
 git branch -M main
 git push -u origin main
 ```

## ¿Cómo creas un repositorio en GitHub?
Tienes que crear primero una cuenta de git y una vez que la creas, github te da la opcion de crear un repo, ya sea publico y privado, solo le tienes que dar nombre y listo, creaste un repo en github.
## ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?
Con una linea que puse mas arriba:
```
 git remote add origin https://github.com/TuNombreDeUsuario/NombreDeTuRepo.git
```
## ¿Cuál es el flujo básico de trabajo en Git y GitHub?
Working Directory: Es la carpeta en tu sistema donde estas trabajando.
Staging Area: Es el "lugar" donde se indexan tus cambios en el repo antes de hacer push.
Local Repository: Es el "lugar" correspondiente cuando ya hiciste commit, aqui ya se registraron los cambios en el repositorio de git.
Remote Repository: Es el directorio remoto donde se almacenan los cambios en github.