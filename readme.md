# COMANDOS BÁSICOS DE GIT

# Create a new repository on the command line
    git init                                        //Arrancamos git
    git add .                                       //Todos los archivos dentro del fichero
    git commit -m "first commit"                    //Hacemos un commit
    git branch -M main                              //Definimos la rama donde queremos haces cambios
    git remote add origin <url del repositorio>     //Administra el conjunto de repositorios de la rama
    git push -u origin main                         //Subimos los archivos seleccionados a GitHub

# Push an existing repository from the command line
    git remote add origin <url del repositorio>     //Administra el conjunto de repositorios de la rama(no es neccesario si se ha hecho el git remote anteriormente)
    git commit -m "commit"                    //Hacemos un commit
    git branch -M main                              //Definimos la rama donde queremos haces cambios
    git push -u origin main                         //Subimos los archivos seleccionados a GitHub



# Import code from another repository
    git clone <url del repositorio>     //Clonamos un repositorio de GitHub en el PC local

# Delete files
    git rm <file name>          //Eliminamos el archivo del directorio local
    git status                  //Vemos los archivos modificados y eliminados
    git restart HEAD <file>     //Recuperamos el archivo eliminado

# OTROS COMANDOS
    git config -l   //Muestra la configuración de git
    git status      //Muestras las modificaciones respecto al último commit y la rama donde estamos
    git checkout    //Muestra los cambios respecto al último commit
