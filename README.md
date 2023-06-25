# Curso Docker 2023

1. Introducción a Docker
	* Introducción a los contenedores
    * Introducción a Docker
    * Instalación de Docker Engine en Linux
    * Instalación de Docker Desktop en Linux
    * Instalación de Docker Desktop en Windows
    
2. Primeros pasos con Docker
    * El "Hola Mundo" de Docker 
    * Ejecución simple de contenedores
    * Ejecutando un contenedor interactivo
    * Creando un contenedor demonio
    * Creando un contenedor con un servidor web
    * Configuración de contenedores con variables de entorno 

3. Gestión de imágenes en Docker
    * Registros de imágenes: Docker Hub
    * Gestión de imágenes
    * ¿Cómo se organizan las imágenes?
    * Creación de contenedores desde imágenes
    * Ejemplo: Desplegando la aplicación mediawiki 

4. Almacenamiento en Docker
    * Los contenedores son efímeros
    * Volúmenes Docker y bind mount
    * Asociando almacenamiento a los contenedores: volúmenes Docker
    * Asociando almacenamiento a los contenedores: bind mount
    * Ejemplo 1: Contenedor nextcloud con almacenamiento persistente
    * Ejemplo 2: Contenedor mariadb con almacenamiento persistente
    * Otros usos del almacenamiento 

5. Redes en Docker
    * Introducción a las redes en Docker
    * Tipos de redes en Docker
    * Gestionando las redes en Docker
    * Uso de la red bridge por defecto
    * Uso de las redes bridge definidas por el usuario
    * Convertir el uso de la red bridge por defecto por una definida por el usuario
    * Ejemplo 1: Despliegue de la aplicación Guestbook
    * Ejemplo 2: Despliegue de la aplicación Temperaturas
    * Ejemplo 3: Despliegue de Wordpress + mariadb
    * Ejemplo 4: Despliegue de tomcat + nginx 

6. Creando escenarios multicontenedor con docker-compose
    * Instalación de docker-compose
    * El fichero docker-compose.yml
    * El comando docker-compose
    * Almacenamiento con docker-compose
    * Redes con docker-compose
    * Ejemplo 1: Despliegue de la aplicación guestbook
    * Ejemplo 2: Despliegue de la aplicación Temperaturas
    * Ejemplo 3: Despliegue de WordPress + Mariadb
    * Ejemplo 4: Despliegue de tomcat + nginx
    * Ejemplos reales de despliegues usando docker-compose 

7. Creación de imágenes en Docker 
    * Creación de imágenes a partir de un contenedor
    * Creación de imágenes a partir de un Dockerfile
    * Distribución de imágenes
    * Ejemplo 1: Construcción de imágenes con una página estática
    * Ejemplo 2: Construcción de imágenes con una una aplicación PHP
    * Ejemplo 3: Construcción de imágenes con una una aplicación Python
    * Ciclo de vida de las aplicaciones 

8. Docker Desktop
    * Introducción a la interfaz de Docker Desktop
    * Conectar Docker Desktop a la cuenta de Docker Hub
    * Gestión de imágenes
    * Gestión de contenedores
