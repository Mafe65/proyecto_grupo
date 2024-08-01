# proyecto_grupo
## Objetivo: Familiarizarse con el uso de Git en un entorno colaborativo1.

### Actividades:

Configuración Inicial de Git: Configurar el nombre de usuario y correo electrónico.
Crear un Repositorio en GitHub: Crear y clonar un repositorio2.
Inicializar el Proyecto: Crear archivos y estructura básica, realizar un commit inicial.
Trabajo en Ramas: Crear ramas, realizar cambios y commits3.
Merge y Resolución de Conflictos: Enviar cambios, crear pull requests y resolver conflictos4.
Colaboración y Pull Requests: Revisar y aprobar pull requests, actualizar el repositorio local.
Materiales Necesarios: Computadora con acceso a internet, Git instalado, cuenta en GitHub, equipo de 3-4 estudiantes


Comandos utilizados:

git config --global user.name "Tu Nombre"

git config --global user.email "tu.email@ejemplo.com"

git clone [Link del grupo]

mkdir <carpeta> #Creacion de carpetas del proyecto

git add .

git commit -m "Initial commit"

git push origin main

git checkout -b nombre_rama

git checkout nombre_rama_para_cambiar_entre_ramas

git push origin nombre_rama

git checkout main

git merge nombre_rama

git push origin main

git pull origin main
