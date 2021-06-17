# COMANDOS BÁSICOS DE GIT

Create a new repository on the command line:
    git init
    git add .  //Todos los archivos dentro del fichero
    git commit -m "first commit"
    git branch -M main
    git remote add origin <url del repositorio>
    git push -u origin main

Push an existing repository from the command line:
    git remote add origin <url del repositorio>
    git branch -M main
    git push -u origin main

Import code from another repository:
    git clone <url del repositorio>


# OTROS COMANDOS
    git config -l   //muestra la configuración de git
    git checkout    //muestra los cambios respecto al último commit