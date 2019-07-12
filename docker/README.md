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
## 4. Docker en CLI
## 5. Dockerfile
## 6. Instalar Docker Compose
## Instalar
```bash
sudo curl -L "https://github.com/docker/compose/releases/download/1.24.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose \
&& sudo chmod +x /usr/local/bin/docker-compose
```
### Probar instalación
```bash
docker-compose --version
```
## 7. Ejemplos con Docker Compose
