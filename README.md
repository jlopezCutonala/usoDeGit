usoDeGit
========

Tutorial para usar git

1.- Crear cuenta en github.com e instalar git en el equipo local.
2.-Configurar git
    git config --global user.name "Mi nombre"
    git config --global user.email micorreo@correo.com

3.-Crear repositorio en github
4.-Clonar el repositorio con la url que github proporcione

    git clone https://github.com/jlopezCutonala/p3_practica1.git

    cd p3_practica1

5.-Crear rama develop

    git checkout -b develop
6.-Verificar ramas

    git branch
        *develop
         master

7.- Trabajar, colocar el proyecto dentro de la carpeta del repositorio.
Realizar el primer commit

git gui

Presionar botón rescan, pasar los archivos del area de trabajo superior a la inferior presionando sobre los iconos de los archivos, colocar un mensaje y presionar el botón commit.

8.- Realizar algún cambio en los archivos.

9.- Realizar el segundo commit.
git gui 

Presionar botón rescan, pasar los archivos del area de trabajo superior a la inferior presionando so
bre los iconos de los archivos, colocar un mensaje y presionar el botón commit.

10.- Realizar el cambio de rama.

git checkout master

6.-Verificar ramas

    git branch
        develop
        *master

13.- Mezclar las ramas.

git merge develop

14.- Subir rama master a github

git push origin master

15.- Verificar que los archivos esten en github.
