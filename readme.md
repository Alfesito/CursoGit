# COMANDOS BÁSICOS DE GIT
Documentación: https://bluuweb.github.io/tutorial-github/guia/fundamentos.html 
# Create a new repository on the command line
    git init                                        //Arrancamos git
    git add .                                       //Todos los archivos dentro del fichero
    git commit -m "first commit"                    //Hacemos un commit
    git branch -M main                              //Creamos una rama
    git remote add origin <url del repositorio>     //Administra el conjunto de repositorios de la rama
    git push -u origin main                         //Subimos los archivos seleccionados a GitHub

# Push an existing repository from the command line
    git checkout <rama>                             //Nos movemos a la rama
    git commit -m "commit"                          //Hacemos un commit
    git push -u origin main                         //Subimos los archivos seleccionados a GitHub

# Import code from another repository
    git clone <url del repositorio>     //Clonamos un repositorio de GitHub en el PC local

# Delete files
    git rm <file name>          //Eliminamos el archivo del directorio local
    git status                  //Vemos los archivos modificados y eliminados
    git restart HEAD <file>     //Recuperamos el archivo eliminado

# Uso de ramas
    git log                                                 //Vemos los commits con sus ids y la fecha
    git log --oneline                                       //Vemos la rama actual
    git checkout <rama>                                     //Nos movemos a la rama
    git checkout <6primeros dígitos id del commit>          //Volvemos a un commit anterior
    git merge <rama que quieres juntar al main>             //Unimos una rama al main o master
    git branch -d <rama a eliminar>                         //Eliminar una rama
    
# OTROS COMANDOS
    git config -l   //Muestra la configuración de git
    git status      //Muestras las modificaciones respecto al último commit y la rama donde estamos
    git checkout    //Muestra los cambios respecto al último commit
    git branch      //Muestra las ramas existentes
