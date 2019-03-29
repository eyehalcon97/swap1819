# swap1819
Practica 1:

Para empezar nos iremos a configuracion del la virtualbox -> administrador de redes Anfitrion
Alli crearemos una tarjeta de red virtual y la añadiremos a la maquina virtual antes de la instalacion para asi tener una configuracion de esta en la instalacion.

![Red Anfitrion](./capturas/img1.1.jpg)

Comenzaremos con la instalacion de Ubuntu server 16.04

![Instalacion](./capturas/img1.2.jpg)

Al configurar la red antes de la instalacion, el sistema operativo reconoce ambas redes.

![Instalacion2](./capturas/img1.3.jpg)

Durante la instalacion podemos seleccionar que nos instale el LAMP y ssh service.

![Instalacion LAMP](./capturas/img1.4.jpg)

Ahora una vez hecho esto nos vamos a /etc/network/interfaces y configuramos la segunda interfaz que es la que nos da conexion entre los dos servidores

![Interfaces](./capturas/img1.5.jpg)

Una vez asignado la ip haremos ifup enp0s8 y con ello se activara la red
Una vez hecho esto en ambos seridores y configurado su propia ip habremos conseguido que se hagan ping entre ellas y que se puedan conectar mediante ssh

![SSH](./capturas/img1.6.jpg)
