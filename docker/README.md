# Conocimientos Básicos de Docker
## Pasos sugeridos.
- 01 - Leer las diapositivas [Docker conocimientos básicos.pptx](https://github.com/burongtz/apuntes/raw/master/docker/Docker%20conocimientos%20b%C3%A1sicos.pptx). \
Este archivo contiene algunos conceptos básicos de Docker.
- 02 - Instalar Docker.
- 03 - Probar los ejemplos propuestos.
- 04 - Instalar Docker Compose.
- 05 - Probar los ejemplos propuestos.
- 05 - Ver los comando más utilizados.

## Instalar Docker

### Instalar Docker en windows
https://docs.docker.com/docker-for-windows/install/

[¿Qué debo saber antes de intalar Docker?](https://docs.docker.com/docker-for-windows/install/#what-to-know-before-you-install)

- 01 - Descargar el intalador desde [download.docker.com](https://download.docker.com/win/stable/Docker%20for%20Windows%20Installer.exe)
- 02 - Siga el asistente de intalación
- 03 - Haga clic en Finalizar en el cuadro de diálogo de instalación completa para iniciar Docker.

### Instalar Docker en linux
https://docs.docker.com/install/linux/docker-ce/ubuntu/#install-using-the-convenience-script

- 01 - Descargar el script [get-docker.sh](https://get.docker.com/)
- 02 - Ejecutar el script 
```bash
$ chmod +x get-docker.sh
$ ./get-docker.sh
# Una ves instalado puedes revisar la versión
$ docker --version
```