# Comandos-Sistemas-Operativos
Comandos para usar en la maquina virtual de linux

| Comando |  Descripcion  |  Ejemplo |
| ------- | ------------- | ---------|
 Sudo Su |  El comando (sudo su) permite a los usuarios ejecutar programas con los privilegios de seguridad de otro usuario (normalmente el usuario root) de manera segura.  |  el comando (sudo) con la opción (-h) que significa (help/ayuda) muestra un mensaje de ayuda con los usos de sudo. |
Man|  se utiliza para acceder a la documentación disponible de sus herramientas y así aprender sobre comandos, archivos, llamadas de sistema, etc.  |  invoquemos el manual del comando free, quien es utilizado para ver el consumo de memoria RAM desde la consola. |
whoami |  Es un comando simple, utilizado para imprimir el nombre de usuario efectivo del usuario actual cuando se invoca, que se entiende como el nombre del usuario en sesión  |  Para saber la versión de whoami que estamos utilizando, nos basta con utilizar la opción –versión |
More |  permite mostrar el resultado de la ejecución de un comando en la terminal de a una página a la vez.  |  si deseas leer un archivo de texto de a una página a la vez, usa el comando more por sí mismo de la siguiente manera :more <nombre del archivo> |
tail -n |  Este comando sirve para identificar donde estan los errores de algun programa o archivo que se este utilizando.  |  Al usar este comando: tail -f /var/log/syslog mostrara una serie de errores. |
head -n |  en caso de que desee ir al inicio de un fichero  |  head -20 <filename> |
cp |   copiar uno o más archivos a una ubicación especificada por el usuario |  En este ejemplo, creamos un nuevo archivo en la carpeta de destino que tiene el mismo nombre que el archivo de origen. cp texto.txt /home/usuario/carpeta_de_destino/ |
alias |  Los alias son muy útiles cuando se trata de trabajar rápidamente en Linux. Podemos usar alias para ejecutar un comando de memoria larga o difícil con una palabra simple. Hay dos tipos de alias: temporales y permanentes.  |  Alias temporal: alias alias_name=’command’ |
passwd |  se usa para cambiar la contraseña de un usuario  |  Su sintaxis es de la forma: passwd [opciones] [USUARIO] |
useradd |   crear usuarios desde el terminal. |  useradd [options] nombre_de_usuario |
mv |  para mover o cambiar el nombre de archivos y directorios  |  Para mover file_1.txt del directorio actual a otro directorio: $ mv file_1.txt /home/pungki/office  |
rm |  Se usa para eliminar archivos  |   [code] rm myfile.txt [/code]Elimina el archivo myfile.txt. Si el archivo está protegido contra escritura, te pedirá que confirmes que realmente deseas eliminarlo. | 
rm -R |  Como rm es un comando muy destructivo, es posible que elimine accidentalmente archivos importantes. La buena noticia es que rm tiene un indicador -i que le pide (para confirmar) antes de eliminar cada archivo.  |   digamos que desea eliminar el archivo. hello.txt pero desea que rm le pida que confirme la operación de eliminación del archivo.|
history |  para averiguar los últimos comandos que se han ejecutado en un Servidor  |  para verificar ultimos 25 comandos: # history 25  |
ls -l |  función principal es la de listar ficheros y directorios, por defecto alfabéticamente.  | Listar el directorio actual, el directorio Descargas y el directorio /usr/localls . Descargas/ /usr/local |
Deb |  Permite la instalación de paquetes RPM  |  sudo dpkg -i google-chrome-stable_current_amd64.deb |
 neofetch |  Neofetch es un programa de información del sistema CLI escrita en BASH, este muestra la información sobre el sistema junto a una imagen  |  sudo add-apt-repository. |
screenfetch|  Screenfetch es una herramienta de información Bash Screenshot. Este práctico script Bash, desarrollado por Brett Bohnenkamper y de código abierto, se utiliza para generar una ingeniosa ficha que provee información sobre la distribución que se está usando, donde nos imprimirá por consola datos como: el tema del terminal, versión del kernel, el entorno de escritorio, CPU, RAM, y logotipos según la distribución en ASCII.  |  sudo apt-get install screenfetch |
apt install  |  Este comando se usa para instalar la versión más nueva de todos los paquetes instalados en el sistema. Los paquetes instalados con una nueva versión disponible se descargan y actualizan, y bajo ninguna circunstancia se desinstalarán paquetes, o se instalarán paquetes nuevos.  | En este ejemplo procedimos a instalar el servidor DNS bind9 de la siguiente manera: apt-get install bind9  |
Snap |  El comando snap es equivalente al comando apt, pero puede usarlo para instalar software desde la Snap Store, en lugar de paquetes desde los repositorios Apt.  |  sudo snap install snapcraft --classic |
sudo apt update |  Apt-get update sirve para actualizar los repositorios que definimos en el archivo /etc/apt/sources.list. Se actualizan los listados de paquetes disponibles en las fuentes definidas en el archivo sources.list, pero no instala nada. Lo que hace es ver si hay nuevas versiones de los paquetes que tenemos en las fuentes definidas, pero sin modificar nada en nuestro sistema.  |  sudo apt-get upgrade |
snap find |  El software Snap son paquetes independientes con todas las bibliotecas dependientes incluidas, lo que hace que la instalación sea mucho más sencilla. Como los paquetes están en contenedores, las aplicaciones se aíslan y los cambios no afectarán a otros sistemas.  |  $ sudo apt install snapd |
sudo snap install | gestionar e instalar aplicaciones en Ubuntu.   |  Para hacer la instalación, el proceso es sencillo, sólo se ha de escribir : sudo snap install «nombre paquete» y se procederá a la instalación de dicho programa. Algo sencillo que tienen las últimas versiones de Ubuntu, las versiones más viejas u otras distribuciones tienen que instalar snap o snapcraft primero para que funcione. |
a |  b  |  c |
a |  b  |  c |
a |  b  |  c |
a |  b  |  c |
a |  b  |  c |
a |  b  |  c |
 
 
