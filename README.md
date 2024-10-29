# Tarea-06---SXE

### Utiliza docker para poner en marcha Prestashop
Vamos a crear nuestro docker compose. Creamos el fichero "docker-compose.yml" para ello nos ubicamos en el directorio donde queremos guardarlo y con el siguiente comando lo creamos:

``touch docker-compose.yml``

Editamos el docekr compose donde insertamos las imagenes de la base de datos y la imagen de prestashop.

``nano /home/Compose/docker-compose.yml``

![imagen1](Imagenes/punto1.pgn)

Ahora vamos a lanzar nuestro docker compose, para ello debemos asegurarnos de estar en el directorio donde esta creado nuestro fichero "docker-compose.yml", ponemos los siguientes comando:

``docker-compose up -d``

![imagen2](Imagenes/punto2.png)

Esto va a crear contenedores donde se encuentren las imagenes que se especificaron en el docker-compose y los va a ejecutar. 

![imagen2.1](Imagenes/punto2_1.png)

Luego de tener ejecutado los contenedores, vamos a ir al navegador y poner el host con el puerto que hemos especificado en el docker compose  http://10.0.9.98:4080  y si todo ah esatdo correcto se visualiza la pagina del Prestahop

![imagen3](Imagenes/punto3.png)

