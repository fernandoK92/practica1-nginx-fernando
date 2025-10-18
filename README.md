# Práctica Contenedores servidor web 

## 1. Título  
Contenedores servidor web
## 2. Tiempo de duración  
25 minutos.  

## 3. Fundamentos  

En esta práctica usamos Docker para crear contenedores y correr en ellos el servidor web Nginx.
Un contenedor es como una “cajita” que trae todo lo necesario para que una aplicación funcione sin depender del sistema principal.

Con Nginx montamos dos páginas distintas:

Una con información del instituto.

Otra con información personal del estudiante.

Para personalizar el contenido, copiamos el archivo index.html desde el contenedor al computador, lo editamos y lo volvimos a pasar al contenedor.

El objetivo es aprender a manejar contenedores, editar archivos dentro de Linux y entender cómo desplegar páginas web básicas de forma rápida y aislada.

## 4. Conocimientos previos  

Para poder realizar esta práctica es necesario tener unas nociones básicas de:

Linux: conocer comandos básicos como copiar, mover, editar y navegar entre carpetas.

Docker: saber qué es un contenedor y cómo se ejecuta con docker run, docker ps, docker stop.

Nginx: entender que es un servidor web y que muestra por defecto el archivo index.html.

Markdown y GitHub: para poder documentar la práctica en un informe y subirlo al repositorio.

## 5. Objetivos a alcanzar  

Objetivo general

Aprender a crear y personalizar servidores web en contenedores Docker usando la imagen de Nginx.

Objetivos específicos

Crear dos contenedores Nginx y exponerlos en diferentes puertos.

Editar y personalizar el archivo index.html de cada servidor.

Practicar el uso de comandos básicos de Docker para copiar, ejecutar y administrar contenedores.

Documentar la práctica en un informe usando formato Markdown y subirlo a GitHub.
  
## 6. Equipo necesario  

Computador personal con Windows, Linux o macOS.

Docker Desktop instalado y funcionando.

Editor de texto (Bloc de notas, VS Code, Nano, etc.) para modificar los archivos HTML.

Navegador web (Chrome, Firefox, Edge) para visualizar las páginas desplegadas.

Conexión a internet para descargar la imagen de Nginx desde Docker Hub.

Cuenta en GitHub para subir el informe en formato Markdown.

## 7. Material de apoyo  

- Documentación de Linux.
- Documentacion de Docker
- Videos de youtube. 
- Tutoriales de Docker.
## 8. Procedimiento    

1) Verificamos que docker este bien en nuetra pc 

Abrir Docker Desktop y una terminal PowerShell (o CMD).

Comprobar que Docker corre:
<img width="541" height="85" alt="image" src="https://github.com/user-attachments/assets/e31e4eed-0044-48f6-8a0c-6bc9d3d43fb9" />

2) Crear los contenedores Nginx

Creamos dos contenedores (uno para la informacion institucional y otro para la informacion personal):
<img width="1015" height="315" alt="image" src="https://github.com/user-attachments/assets/69024d56-c9e2-45ba-b52c-954ae5167341" />

<img width="877" height="63" alt="image" src="https://github.com/user-attachments/assets/66d8e530-6e4f-42ac-a3b1-35ede3f6de61" />



