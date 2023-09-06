Configurar un repositorio nuevo desde terminal.
1. git init , inicializa un repositorio vacio en nuestra carpeta.
2. git add . todos los archivos que tienen cambios  son agregados.
3. git commit -m "dejar un mensaje" este comando es el que crea la versión nueva con los cambios actuales, pero sin eliminar la previa.
4. ir a github y crear un repositorio vacio inicializa el repositorio en nuestra cuenta  github
5. git add remote origin url-del-github-vacio  enlaza el repositorio de nuestra cuenta con el repositorio de nuestra carpeta
6. git push -u origin master, actualiza la versión actual  de nuestra   carpeta  en el repositorio de nuestra cuenta



Generar una nueva versión  y actualizar el repositorio

git add .
git commit -m "Un nuevo Mensaje"
git push -u origin main
