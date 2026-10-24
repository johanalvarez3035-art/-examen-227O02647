# Examen práctico 2 - 227O02647

\# Examen práctico 2 - 227O02647



\## Objetivo del proyecto

Desplegar una aplicación web en tres servicios independientes con Docker Compose

y gestionar el proyecto con Git y GitHub.



\## Imagen utilizada

examen:227O02647 (basada en nginx:alpine)



\## Puertos

8081, 8082 y 8083 del equipo anfitrión (cada uno apunta al puerto 80 del contenedor).



\## Cómo levantar los servicios

docker build -t examen:227O02647 .

docker compose up -d

docker compose ps

'@



