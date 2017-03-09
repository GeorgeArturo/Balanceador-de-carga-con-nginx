# Balanceador-de-carga-con-nginx
Autor:

Estudiante: Jorge Arturo Hernández Muñoz
Código: A00317220

El reto de este ejercicio era hacer un balanceador de carga, habían distintas formas de implementarse como por ejemplo apache,
nginx etc. Yo use gnix así que para empezar tuve que instalar gnix. Prueba de instalación de gnix:

**Inserte imagen aqui**


Una vez hecho esto lo que se hizo fue que de manera automática, se conectara con las webs y que estas se conectarán a la 
base de datos, para así poder balancear.


Vagrantfile:
A continuación  se muestra la configuración del vagrantfile.
(Este archivo esta disponible en este repositorio)
Aquí se ve la configuración de :

web1.
web2.
Base de datos (db).
balanceador (bl).

esta configuración incluye la ip pública, ip privada, las interfaces, la box que está usando, el nombre que se le va a dar 
a la máquina, los cookbooks y los récipes con que debe configurarse.

**Inserte imagen aqui**

A continuación se muestran como se configuraron los cookbooks (Los cookbooks estan dsponibles en este repositorio)

**Inserte imagen aqui**

finalmente una prueba de funcionamiento:

**Inserte gift aqui**


Documentación de problemas.

Para esta actividad solo tuve un problema el cual fue que cuando se instaló gnix este venia con una url por defecto,
url que descargaba un repositorio con lo que hacía falta para realizar el balanceador. esta url no servía así que 
lo que se hizo fue entrar al archivo de configuración y cambiar la url del repositorio así cuando se hiciera el 
aprovisionamiento instalará los paquetes correctos.

**inserte imagen aqui**

## Todos los archivos estan disponibles en este repositorio.
