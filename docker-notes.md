# 🐳 Docker Quickstart - Angie Henriquez

Este repositorio contiene ejemplos básicos de *Docker*, siguiendo el curso "Introducción a Docker - Coursera".

---

## 📌 Conceptos Clave
- *Imagen:* plantilla que define lo que corre en el contenedor (ejemplo: Ubuntu, Nginx, MySQL).  
- *Contenedor:* instancia ejecutándose de una imagen.  
- *Repositorio:* almacén de imágenes en *DockerHub* o local.  

---

## 🔧 Comandos Básicos
```bash
# Descargar una imagen desde DockerHub
docker pull nginx

# Listar imágenes descargadas
docker images

# Crear y ejecutar un contenedor
docker run -d -p 8080:80 nginx

# Ver contenedores en ejecución
docker ps

# Detener un contenedor
docker stop <container_id>

# Eliminar un contenedor
docker rm <container_id>

# Eliminar una imagen
docker rmi nginx
