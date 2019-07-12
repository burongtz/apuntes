# Conocimientos Básicos de Docker

## 1. [Introducción](./pages/1._leer_diapositivas.md)
## 2. Instalar Docker (Ubuntu)
### Configurar el repositorio
```bash
sudo apt-get update \
&& sudo apt-get install -y apt-transport-https curl gnupg-agent software-properties-common \
&& curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - \
&& sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
```

### Instalar Docker CE
```bash
sudo apt-get update \
&& sudo apt-get install -y docker-ce docker-ce-cli containerd.io
```
### Probar que se instaló correctamente
```bash
sudo docker run hello-world
```

### Agregar el usuario al grupo Docker
```bash
sudo usermod -aG docker "$USER"
```
## 3. Ejemplos con Docker.
### 3.1. Docker en CLI
### 3.2. Dockerfile
* 4\. [Instalar Docker Compose](./pages/4._instalar_docker_compose.md#instalar-docker-compose)
* 5\. Ejemplos con Docker Compose
