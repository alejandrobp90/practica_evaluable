# practica_evaluable
21. Añade a tu repositorio remoto un archivo README.md. En el añade una breve descripción del ejercicio que acabas de realizar. Añade los comandos Git empleados durante la tarea.

    
En esta serie de ejercicios hemos realizado una serie de acciones orientadas al uso de Github mediantes comandos desde la consola Git bash. Hemos navegado entre carpetas, creado la carpeta donde iniciar nuestro repositorio, creado archivos y modificado, del working al staging, los hemos commiteado, hemos creado y borrado ramas, cambiado entre estas, hemos sincronizado nuestro repo remoto con nuestro local, hemos hecho push y pull, creado etiquetas, revertido cambios mediante resetHard a commits anteriores, hemos creado conflictos,... entre otros.

Comandos + comandos git.

Al inicio cambiamos las carpetas con cd .. o cd nombre de carpeta.

Creamos carpeta con mkdir nombrecarpeta.
Comenzamos proceso git:
- git init //Inicializamos repo local
- echo "texto">nombre.txt //Creamos documentos
- ls -la // Mostramos contenido carpeta
- git add nombre.txt o git add . // Del working al staging, es decir, del area de trabajo al area de prepación
- git status // Vemos el estado de nuestro repositorio. Pre git add veremos en rojo, post git add en verde
- git commit -m "texto" // Hacemos commit o validamos lo que hemos hecho
- echo "texto">>nombre.txt // Modificamos nuestro archivo con linea de texto
- git log // Vemos la informacion de nuestros commits de manera más amplia
- git log --oneline // Vemos la info pero reducida
- git reset --hard codigoCommit // Volvemos a un estado anterior, como restaurar una imagen
- cat nombre.txt //vemos el texto del archivo
- git remote add origin https //Vinculamos nuestro repo remoto a nuestro local
- git remote -v // Vemos que repo está vinculado
- git branch -m master main // renombramos rama master a main para evitar errores en git
- git pull origin main // Actualizamos nuestro local con el remoto
- git push origin main // Actualizamos nuestro remoto con nuestro local
- git branch -v -a // mostramos información detallada sobre las ramas locales y remotas de nuestro repo Git
- git branch nombre // creamos rama llamada nombre
- git checkout nombre // cambiamos a rama nombre
- git merge nombre//git merge nombre main // Fusionamos la rama nombre con nuestro main
- git branch // Vemos nuestras ramas
- git branch -d nombre // Borramos dicha rama
- git tag -a V1 -m "texto" // Creamos etiqueta con más informacion y texto
- git push origin --tags // Subimos nuestras etiquetas al remoto
- git clone https //Clonamos nuestro remoto en la carpeta que estemos, no hay que hacer git init
- git push origin --delete nombre // borramos en el remoto la rama nombre
- nano nombre.txt // editamos nuestro documento, guardamos con control+o y cerramos con control+x
  
