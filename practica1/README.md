# swap1819
Practicas Swap
Servidores Web de Altas Prestaciones
Practica 1:

Para empezar nos iremos a configuraci�n del la virtualbox -> administrador de redes Anfitri�n
All� crearemos una tarjeta de red virtual y la a�adiremos a la maquina virtual antes de la instalaci�n para asi tener una configuraci�n de esta en la instalaci�n.
![Red Anfitrion](/capturas/img1.1.jpg)

Comenzaremos con la instalaci�n de Ubuntu server 16.04
![Instalacion](/capturas/img1.2.jpg)

Al configurar la red antes de la instalaci�n, el sistema operativo reconoce ambas redes.
Durante la instalaci�n podemos seleccionar que nos instale el LAMP y ssh service.


Ahora una vez hecho esto nos vamos a /etc/network/interfaces y configuramos la segunda interfaz que es la que nos da conexi�n entre los dos servidores

Una vez asignado la ip haremos ifup enp0s8 y con ello se activara la red
Una vez hecho esto en ambos seridores y configurado su propia ip habremos conseguido que se hagan ping entre ellas y que se puedan conectar mediante ssh
