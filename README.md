# sistemas_operativos
Bitácora de Comandos

SEMANA 2

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
* `nano [nombre del archivo con el formato]` edita un archivo. 
* `cat [nombre del archivo con el formato]` muestra el contenido del archivo en el CLI.
* `ps -aux` información de procesos. 
  * `ps -aux | grep [parametro de búsqueda]` se obtiene información de procesos por medio de un parámetro específico.
* `kill –9 [numero del proceso]` elimina un proceso. 
* `pstree` árbol de procesos.

SEMANA 3 

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
* sudo add-apt-repository ppa:numix/ppa -y [agregar un repositorio]. 




