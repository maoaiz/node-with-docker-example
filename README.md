# Node con Docker 

Comandos para correr la app en local

```
sudo docker build . -t <IMAGE_NAME>

# ver las imágenes
sudo docker images

# Correr el container
sudo docker run --name <CONTAINER-NAME> -p <YOUR_PORT>:3000 -d <IMAGE_NAME>


# Ver el contenedor corriendo
sudo docker ps

# Conectarse al contenedor
sudo docker exec -it <CONTAINER-NAME> bash

```


Probar en localhost:<YOUR_PORT>
