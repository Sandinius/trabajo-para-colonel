# trabajo-para-colonel
Este proyecto contiene una página web desarrollada con **HTML, CSS y JavaScript**, y está configurado para ejecutarse en un contenedor Docker usando **Nginx** como servidor web.

#Requisitos
- Tener [Docker Desktop](https://www.docker.com/products/docker-desktop) instalado y funcionando.

## Instrucciones para levantar el proyecto

### 1. Clonar el repositorio

```bash
git clone https://github.com/Sandinius/trabajo-para-colonel.git
cd trabajo-para-colonel.git
```
### 2. Contruir la imagen de docker

```bash
docker build -t proyecto-docker-ingenieria .

docker run -d -p 8080:80 --name proyecto-web-ing proyecto-docker-ingenieria
```
### 3.Esto levantara el sitio en: 

- [text](http://localhost:8080/)