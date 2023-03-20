# COMANDOS BÁSICOS DE PRÁCTICA GIT PARA LA TERMINAL DE GIT BASH

>`cd` : nos permite cambiarnos de carpeta, **p.ej.** cd NuevaCarpeta.

>`cd .. ` : nos permite regresar al directorio o carpeta anterior.

>`cd o cd ~` : nos lleva a la ruta del usuario.

>`cd /c` : nos vamos al disco C:/.

>`cd -` : nos lleva directamente al ultimo directorio visitado.

>`ls` : nos permite ver los archivos de la carpeta donde estamos actualmente.

>`ls -l` : Ver todos los archivos como una lista en donde incluye el usuario, grupo, permisos sobre el archivo, tamaño, fecha y hora de creación.

>`ls -lh` : Muestra la misma información que ls-l pero con unidades de tamaño, es decir, kb o mb.

>`ls-R` : muestra el contenido de todos los sudirectorios de forma recursiva.

>`ls -S` : Ordena los resultados por tamaño de archivo.

>`PWD` :Nos muestra la carpeta actual en la que nos encontramos.

>`pwd` : nos muestra la carpeta actual en la que nos encontramos.

>`mkdir` : nos permite crear carpetas, **p.ej.** mkdir NuevaCarpeta

>`touch` : nos permite crear archivos nuevos, **p.ej.** touch NuevoArchivo.txt

>`cat` : nos permite ver el contenido de un archivo, **p.ej.** cat NuevoArchivo.txt

>`rm` : Nos permite borrar un archivo o carpeta ej: **rm NuevoArchivo.txt**

>`rmdir <<nombre del directorio>>` : borrar un directorio: **Solo funciona con directorios vacíos.**

>`rm -r <<nombre de la carpeta>>` : me permite eliminar la carpeta y los archivos dentro de ella de forma recursiva.

>`cp <<nombre del archivo que quremos copiar>> <<nombre del directorio a donde lo queremos copia>>`: nos permite copiar un archivo.

>`mv <<el directorio de donde queremos mover>> <<el nombre del archivo el directorio hacia donde lo queremos mover>>` : **nos permite mover un archivo.**

>`clear` : nos permite limpiar la pantalla.

>`history` : ver los últimos comandos que ejecutamos y un número especial con el que podemos volver a repetir el comando.

---
# Los tres estados de GIT

> Git
tiene tres estados principales en los que se pueden encontrar tus archivos:
>1. **Confirmado (committed)**, significa que los
datos están almacenados de manera segura en tu base de datos local.
>2. **Modificado (modified)**, significa que has modificado el archivo pero todavía no lo has confirmado a tu base de
datos.
>3. **Preparado (staged)**, significa que has marcado un archivo modificado en su versión actual
para que vaya en tu próxima confirmación.

![Los 3 estados de git](./Estados_de_git.png)
