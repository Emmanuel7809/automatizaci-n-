# Comandos
## Instalacion de Docker
INSTALACION
ir a https://docs.docker.com/engine/install/ubuntu/ y seguir las instalaciones.

LINUX MINT:
https://www.linuxtechi.com/how-to-install-docker-on-linux-mint/


## Instlacion de docker 
Instalacion 


Listado de comandos basicos de docker

- *listar las imagenes disponibles en el sistema*

shell
docker ps -a

Inicializar un contenedor: 

    docker start [nombre o ID]

Ver los Logs de los contenedores: 

    docker logs [nombre contenedor]

Detener los contenedores: 

    docker stop [nombre contenedor]

Eliminar un contenedor: 

    docker rm [nombre o ID]

Eliminar una imagen: 

    docker image rm [nombre o ID]

# Repositorio de Docker
[Repositorio](https://hub.docker.com/)

# Crear imagen a partir de un archivo Dockerfile
- * docker build -t nameapp:tag --no-cache
    --build-arg JAR_FILE=target/*.jar .
# Levantar un contenedor a partir de una imagen
- * docker run -p 80:80 -p 8080:8080 --name containername nameapp:tag

# guia basica GIT 
- inicializar git
shell
    git init


- cambiar el nombre de las ramas 
shell
    git branch -m [rama-anterior] [nuevo nombre]
    git branch -m master main


pasar los archivos (modificados y/o )

shell
    git add .


- realizar el commit 
shell
 git commit -m "creacion del proyecto"   


- configuración de usuario y correo 
shell
    git config --global user.name "Emmanuel7809"

    git config --global user.gmail "alanfrancisco7809@gmail.com"