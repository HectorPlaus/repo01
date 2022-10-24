# Ejercicio 1
![Descripción de la imagen](/img/1.PNG)
![Descripción de la imagen](/img/2.PNG)
![Descripción de la imagen](/img/3.PNG)

1. cd desktop: Nos situamos en directorio del Escritorio    
2. mkdir repo01: Creamos el directorio de repo01
3. git init repo01: Inicializamos el directorio como repositorio
4. cd repo01: Nos situamos en el repositorio de Repo01
5. git add readme.md: Añadimos el fichero al repositorio al staging area
6. git status: Visualizamos el estado del repositorio
7. git commit -m "Creo el fichero readme.md": Hacemos un snapshot del fichero hacia nuestro repositorio local
8. git push: No completa el comando debido a que  no se ha asocido el repositorio remoto
9. git remote -v: Tampoco hace nada debido a la falta de remoto
10. git remote add origin https://github.com/HectorPlaus/repo01.git
git branch -M main
git push -u origin main: Asociamos el repositorio remoto
11. git remote -v: Nos muestra que el repositorio remoto se ha asociado correctamente y nos muestra la direccion de este.
12. 


