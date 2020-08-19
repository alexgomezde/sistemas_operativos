# sistemas_operativos
Bitácora de Comandos

* `ip addr` muestra la dirección IP de la computadora.
* `lsb_release -a` muestra la versión del sistema operativo.
* `uname -a` muestra la versión del kernel.
* `ls` muestra los archivos que están en la carpeta.
  * `ls -l` muestra los archivos que están en la carpeta en forma de lista. 
  * `ls -la` muestra los archivos ocultos que están en la carpeta en forma de lista. 
  * `ls [nombre de la carpeta]` muestra los archivos de una carpeta en específico. 
* `mkdir` crear carpeta.
* `cd` cambiar de directorio.
* `pwd` imprime la ruta del directorio actual.
* `touch [nombre del archivo con el formato]` crea un archivo.
* `cp [nombre del archivo] [nombre del archivo con el formato]` copiar archivos o carpetas.
* `mv [nombre o ruta del archivo o directorio que se desea mover] [ruta de destino del directorio]` mover archivos o carpetas.
* `rm [nombre o ruta del archivo o directorio] ` remover archivos o carpetas.
  * `rm -r [nombre de la carpeta]` remover directorios y su contenidos recursivamente. 
* `chmod [permisos] [nombre del archivo o carpeta]` cambiar permisos de archivos y carpetas. 
  * `chmod 644 [nombre del archivo]` el propietario puede leer y escribir, el grupo solo puede leer y otros solo pueden leer. 
* `chown [owner/group owner] [nombre del archivo o carpeta]` cambiar permisos de archivos y carpetas. 
* `nano [nombre del archivo con el formato]` edita un archivo. 
* `cat [nombre del archivo con el formato]` muestra el contenido del archivo en el CLI.
* `ps -aux` información de procesos. 
  * `ps -aux | grep [parametro de búsqueda]` se obtiene información de procesos por medio de un parámetro específico.
* `kill –9 [numero del proceso]` elimina un proceso. 
* `pstree` árbol de procesos.
* `man [comando]` muestra el manual de un comando.
* `sudo su` cambiar a usuario root.
* `whoami` muestra el usuario que esta logueado.
* `cat /var/log/syslog | more` muestra por páginas. 
* `tail –n 10 /var/log/syslog` ultimas (tail) diez líneas del archivo (-n 10).
* `head–n 10 /var/log/syslog` primeras (head) diez líneas del archivo  (-n 10).
* `sudo apt update && sudo apt upgrade` actualiza y después instala.
* `alias actualizar="sudo apt update && sudo apt upgrade"` crear un alias para ejecutar comandos.
* `useradd [nombre del usuario] -p [contraseña]`crear usuario.  
* `passwd  [nombre del usuario]` cambiar el password  de un usuario.
* `history` muestra los comandos digitados.
* `history | grep [parametro]` busca un comando digitado en el historial en base al parámetro especificado.
* `sudo apt remove [package name]` remueve un paquete. 
* `dpkg -i [nombre del paquete]` instalación de paquetes. 
* `!!` corre el ultimo comando 
* `sudo !!` corre el último comando con permisos de administrador.
* `sudo add-apt-repository ppa:numix/ppa -y` agregar repositorio. 
* `sudo add-apt-repository ppa:numix/ppa -y` agregar repositorio. 
* `neofetch` muestra información del sistema operativo, software y hardware de una manera estética y visualmente agradable.
* `ln -s [archivo.orginal] [enlacesuave.archivo]` creación de enlaces suaves.
* `ln [archivo.orginal] [enlaceduro.archivo]` creación de enlaces duros.
* `du -h [nombre del archivo]` tamaño del archivo.
* `stat [nombre del archivo]` fecha de creación, último acceso.
* `file [nombre del archivo]` tipo de archivo.
* `df -h` mostrar el espacio en disco usado.
* `mount` montaje de dispositivos en el sistema de archivos.
* `gparted` administra las particiones.
* `gnome-disk-utility` muestra información sobre el disco.
* `bash --version` muestra la versión bash.
* `[comando] --help` obtener información de comando.
* `shutdown` apagar el sistema operativo.
* `wget [URL]` permite descargar archivos.
* `traceroute [URL]` información acerca de la ruta que toma un paquete que será enviado desde nuestro equipo hasta un host de destino.
* `clear` limpiar la terminal.
* `tar` comprimir archivos y extraerlos.
