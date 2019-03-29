# swap1819
Practicas Swap
Servidores Web de Altas Prestaciones
Practica 1:
 
Para empezar nos iremos a configuración del la virtualbox -> administrador de redes Anfitrión
Allí crearemos una tarjeta de red virtual y la añadiremos a la maquina virtual antes de la instalación para asi tener una configuración de esta en la instalación.
 
Comenzaremos con la instalación de Ubuntu server 16.04
 
Al configurar la red antes de la instalación, el sistema operativo reconoce ambas redes.
Durante la instalación podemos seleccionar que nos instale el LAMP y ssh service.
 

Ahora una vez hecho esto nos vamos a /etc/network/interfaces y configuramos la segunda interfaz que es la que nos da conexión entre los dos servidores
 
Una vez asignado la ip haremos ifup enp0s8 y con ello se activara la red
Una vez hecho esto en ambos seridores y configurado su propia ip habremos conseguido que se hagan ping entre ellas y que se puedan conectar mediante ssh
 

