# Hangman Docker Deployment

## Descripción
Proyecto de despliegue del juego Hangman utilizando Docker y Nginx en un servidor AWS EC2.

## Tecnologías utilizadas
- Docker
- Nginx
- HTML5
- CSS3
- JavaScript
- AWS EC2
- GitHub

## Construcción de la imagen Docker

```bash
sudo docker build -t hangman .
```

## Ejecución del contenedor

```bash
sudo docker run -d -p 80:80 --name hangman hangman
```

## Verificación

```bash
sudo docker ps
```

## Acceso al servicio

Abrir en navegador:

http://IP_PUBLICA_WEB

## Autor

Samuel Rodriguez
CAZ
