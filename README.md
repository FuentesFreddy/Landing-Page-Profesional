# ESPE TECH 104 - Landing Page

## Descripción
Landing page moderna y responsiva para promocionar CV Personal.

## Integrantes

- Freddy Fuentes

## Tecnologías y Herramientas
- HTML5 Semántico
- CSS3 (Flexbox, Grid, Transiciones)
- Docker
- GitHub

## Estructura del proyecto
- `index.html`: Código fuente del sitio.
- `css/styles.css`: Hoja de estilos.
- `Imagenes/`: Recursos visuales institucionales.
- `Dockerfile` y `.dockerignore`: Configuración de despliegue.

## Ejecución Local
1. Construir la imagen: `docker build -t fjfuentes1/landing-prof:latest .`
2. Ejecutar el contenedor: `docker run -d -p 8080:80 espe-tech`
3. Acceder al sitio: http://localhost:8080

## 🐳 Imagen en Docker Hub
- **URL de la imagen:** https://hub.docker.com/r/fjfuentes1/landing-prof
- **Descargar imagen:** `docker pull fjfuentes1/landing-prof:latest`
- **Ejecutar imagen pública:** `docker run -d -p 8080:80 fjfuentes1/landing-prof:latest`