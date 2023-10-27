# Examen COD Sergio de la Iglesia Lorenzo


1. Haz un fork al mismo repositorio del apartado 1 de la primera parte. Vuelve a repetir el apartado 3

Para hacer el fork del repositorio, se accede al enlace del repositorio que queremos clonar, y le damos al botón "Fork" que aparece en la parte superior derecha, sin modificar ningún parámetro, y lo clonamos de forma local ese mismo repositorio. Una vez clonado en local, accedemos a él (cd /ruta) y desde aquí añadimos los nuevos archivos, añadiendo la ruta también con git remote add origin https://github.com/Sergio10326/examenDAM.

2. Añádele el gitignore, complétalo, justifica los ficheros añadidos al gitignore

El archivo .gitignore es un archivo oculto de git que tiene la función de bloquear los archivos que se añadan como texto plano en él para que no se suban a pesar de que seleccionemos todo el contenido de la ruta, por lo que se crea con el comando "touch .gitignore" y se añade una entrada, en este caso añadí "nosubir" y creé el archivo en la misma carpeta, añadimos toda la ruta con "git add ." y hacemos el commit y el push.

touch .gitignore
touch nosubir
sudo gedit .gitignore 
git add .
git commit "gitignore file"
git commit -m "gitignore file"
git push -u origin master
sudo gedit README.md

3. Crea el ejecutable .jar del programa, prueba que funcione


4. Sube el .jar al repositorio remoto
