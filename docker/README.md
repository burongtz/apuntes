# Conocimientos Básicos de Docker

## Índice de contenido.
* 1\. Leer diapositivas
* 2\. Instalar Docker
    * 2.1. Instalar Docker en Windows
    * 2.2. Instalar Docker en Ubuntu
* 3\. Ejemplos con Docker.
    * 3.1. Docker en CLI
    * 3.2. Dockerfile
* 4\. Instalar Docker Compose
* 5\. Ejemplos con Docker Compose

## 2. Instalar Docker

### 2.1 Instalar Docker en windows
https://docs.docker.com/docker-for-windows/install/

[¿Qué debo saber antes de intalar Docker?](https://docs.docker.com/docker-for-windows/install/#what-to-know-before-you-install)

1. Descargar el intalador desde [download.docker.com](https://download.docker.com/win/stable/Docker%20for%20Windows%20Installer.exe)
2. Siga el asistente de intalación
3 Haga clic en Finalizar en el cuadro de diálogo de instalación completa para iniciar Docker.

### 2.2 - Instalar Docker en linux
https://docs.docker.com/install/linux/docker-ce/ubuntu/#install-using-the-convenience-script

1\. Descargar el script [get-docker.sh](https://get.docker.com/) \
2\. Ejecutar el script
```bash
$ chmod +x get-docker.sh
$ ./get-docker.sh
# Una ves instalado puedes revisar la versión
$ docker --version
```