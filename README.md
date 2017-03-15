# JSFexaED
Éste es un proyecto de maven creado como parte del examen de la asignatura de Entornos de Desarrollo del ciclo de Desarrollo de Aplicaciones Web en el IES Polígono Sur de Sevilla, España.

Este proyecto está pensado para ser importado en un IDE del tipo de Spring Tool Suite (STS) y ejecutado bajo un servidor local, como Jetty o el propio Pivotal incluido de STS.

Para poder ejecutar este proyecto con Jetty, debemos:

1. Clonar el repositorio gon git clone.
2. Dentro de la carpeta raíz (/JSFexaED), ejecutar el comando mvn package para proceder a la construccin del archivo .WAR.
3. Ejecutar mvn jetty:run para poner en marcha el servidor local Jetty. Por defecto se pondr en escucha en el puerto 9999. Podemos comprobarlo introduciendo en nuestro navegador localhost:9999 en la barra de direcciones.
