Comando| Descripción| Ejemplo|
|---|---|---|
chmod| Cambia los permisos de las carpetas| chmod 0777 archivo.txt|
chmod + |Lee, escribe y ejecuta |  chmod + holamundo.txt|
chmod -x| Quita los permisos de ejecución| chmod -x holamundo.txt
ls -l| Muestra la lista de los permisos de los archivos| ls/home/nombredeusuario/Documentos|
du | Muestra el tamaño del archivo| du holamundo.txt|
stat| Fecha de creación|stat aprender-linux.txt
chwon|  Tomar posesión del archivo| chown usuariolinux2 archivo.ext|
touch| Actualiza la hora de la fecha de modificación| touch/home/nombredeusuario/Documentos/Web.html|
file| Muestra el formato de un archivo| file holamundo.txt
df | Muestra el espacio en disco utilizado por el sistema de ficheros| ~/Pictures$ df|
mount| Es para montar ciertos dispositivos|mount –t ext2 /dev/hdb2 /temp/aux|
Gparted| Administra las partes del disco duro del sistema|Gparted|
gnome-disk-utility| Administra las unidades de almacenamiento de escritorio| sudo apt install gnome-disk-utility|
kill| Para matar un proceso| kill -9 63772|
ps| Sirve para ver todos los Ids de los programas o procesos| ps -e
greg| Muestra la localización de los procesos| greg -help|
pwd| Directorio actuar donde está uno| /home/nombredeusuario|
nano|Editor de Texto| apt-get install nano|
cat| Leer datos de archivos y mostar su contenido| cat archivo.txt|
cd| Sirve para navegar en los archivos y directorios| cd /home/ nombredeusuario/Peliculas|
cp|Sirve para copiar archivos a diferentes directorios|cp escenario.jpg|
mv| Para mover archivos| mv archivo.txt|
mkdir| Para crear un nuevo directorio| mkdir -p Musica/2020/Nuevoarchivo|
rmdir| Remover directorios vacios| rmdir -p Musica/1950/Viejoarchivo|
rm| Si solo necesita eliminar un directorio| rm -p Musica/1950/Viejoarchivo|
locate| Para localizar un archivo| locate -i escuela|
find| Para buscar archivos y directorios| find /home/ -name notas.txt|
grep| Permite buscar a través de todo el texto de un archivo| grep azul notepad.txt|
sudo|permite hacer tareas que requieran permisos admiistrativos|sudo apt install|
df| Infroma sobre el uso de espacio del disco del sistema| df -m|
head| Para ver las primeras líneas de cualquier texto| head -n 5 nombredearchivo.ext|
tail| Muestra las últimas 10 líneas de un texto| diff archivo1.ext archivo2.ext|
diff| Compara 2 archivos línea por línea| diff archivo1.ext archivo2.ext|
tar| Para guardar multiples archivos|tar archivo1.ext archivo2.ext|
ping| Verificar el estado de conectividad en un servidor|ping google.com|
wget| Para descargar archivos de internet| wget https://downloads.ustility.xyz/netbeans-ide/d25e0d5353cd025abefca|
History | Consulta los comandos utlizados anteriormente | History grep Update
Sudo sh | Ejecuta comandos leídos desde una cadena | Sudo sh
Clear | Borra toda la información del terminal | clear
Man |  Accede a la documentación disponible de sus herramientas | Man mv
Sh | Es un intérprete de comandos en Linux | bin/sh
Touch | Manipular el tiempo de acceso y modificación de los archivos | touch nombre_archivo.txt
Sudo -s | Proporciona un acceso directo para iniciar un shell | sudo -s
Sudo apt-get update | Descarga las listas de paquetes de los repositorios y las actualiza | Sudo apt-get update 
Update | Actualiza la lista de paquetes disponibles y sus versiones | Apt-get update
Exit() | Sirve para salir de modo super usuario a administrador o superusuario | Exit
Run | Suelen ser instaladores de programas | chmod +x archivo.run|
sudo snap install | Nos permite modificar la store |snap find vlc|
Tar | Se utiliza para crear y manipular archivos de almacenamiento | tar -c|
Vnc | Sistema de conexión que le permite usar su teclado y mouse |vncpasswd /etc/vncpass
Sudo apt-get upgrade|  Nos va a instalar todos los paquetes instalados que tengan alguna nueva versión | sudo apt-get upgrade
clean| Nos limpia todo el sistema | apt-get clean
uname| Da la información detalla del sistema| uname|
top| Muestra una lista de procesos en ejecución y cuando CPU utilizan| top|
echo|Se usa para mover algunos datos a un archivo|echo Hola, mi nombre es John >> nombre.txt|
zip| Se usa para comprimir archivos| holamundo.zip|
unzip| Se usa para descomprimir archivos| unzip holamundo.zip|
useradd| Para que más de una persona pueda ejecutar al mismo tiempo| useradd John|
passwd|Para agregar una contraseña al usuario|passwd 123456789|
userdel| Para eliminar un usuario|userdel NombredeUsuario|
Ping 8.8.8.8| Para comprobar la conexión a internet| Ping 8.8.8.8|
shutdown now| Para apagar el sistema| shutdown now -h|
less| Para mostrar el texto en la pantalla de terminal|less -M readme.txt|
more|Muestra el resultado de la ejecución de un comando en la terminal de a una página a la vez|more / etc / passwd|
updatedb| Escanea el sistema completo|cat /etc/updatedb.conf|
netstat| Muestra todos los conexiones activas del pc| netstat -s|
nmap| Para mapear redes| nmap -sS 192.168.1.200|
curl| Para interactuar con un sitio web o un API, enviando peticiones, y mostrando las respuestas a la terminal| curl http://www.google.com| 
