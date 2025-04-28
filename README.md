# Crea el repositorio en GitHub
  1. Crea el repositorio en GitHub
  2. Entra en https://github.com y autentícate.
  3. Haz clic en New repository (o “Nuevo repositorio”).
  4. Ponle un nombre (por ejemplo sena-cinema), elige Public o Private, y deja las opciones “Initialize this repository with a README” sin marcar (porque ya tienes código).
  5. Al crearla, GitHub te mostrará la URL remota (HTTPS o SSH). Cópiala, la vas a usar en el siguiente paso.

# Prepara tu proyecto local
   Abre tu terminal y sitúate en la carpeta donde están tus archivos HTML y CSS:
   cd /ruta/a/tu/proyecto
   Si aún no tienes Git configurado a nivel global, primero define tu nombre y correo:
    
   git config --global user.name "Tu Nombre"
   git config --global user.email "tu@correo.com"
    

# Inicializa el repositorio y haz el primer commit
   1. Inicializas un repositorio Git en tu carpeta
   
   
   git init
   

   2. Cambias el nombre de la rama principal a "main"
   
   git branch -M main
   
    
   3. Añades todos los archivos al área de staging
   
   git add .
   
    
