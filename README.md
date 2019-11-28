# Requisitos

Este repositorio use docker y docker-compose para levantar libertya y
postgresql. Sino tiene docker o docker-compose debe instalarlo primero:

 * docker => https://docs.docker.com/install/linux/docker-ce/ubuntu/
 * docker-compose => https://docs.docker.com/compose/install/

# Crear las imagenes y los containers.

Desde la carpeta del proyecto

`$ docker-compose up -d`

# Accediendo y parando

Si todo salió bien tiene que libertya debería ser accesible desde `localhost:8080`. Para parar los containers se usa:

`$ docker-compose stop`

Revisar la documentaciòn de `docker-compose` para mas opciones.

# ADVERTENCIA

NO usar en producciòn están los passwords hardcodeados!

# Windows

Esta configuración no está probado en windows. Podría funcionar capaz falle
algún permiso.