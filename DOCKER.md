# Guía de Ejecución con Docker para QuimLab

Este documento contiene las instrucciones necesarias para descargar y ejecutar la aplicación QuimLab utilizando contenedores de Docker.

## Requisitos Previos
- Docker debe estar instalado y ejecutándose en tu sistema.

## Cómo ejecutar la aplicación

Para iniciar QuimLab, solo necesitas descargar la imagen preconstruida desde Docker Hub y ejecutarla. Abre tu terminal y lanza el siguiente comando:

```bash
sudo docker run -d -p 8080:80 --name quimlab-container caesaru/quimlab-app
