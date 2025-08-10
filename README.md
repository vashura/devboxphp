# devboxphp
contenedor para desarrollo php
solo se necesita ejecutar el docker-compose y colocar el contenido del proyecto en la carpeta www

para usar el siguiente repositorio solo necesitan clonar este repositorio y 
construir/iniciar/clonar su proyecto en la carpeta wwww

# 1. Clonan TU repositorio base (solo una vez)
git clone https://github.com/tu-usuario/mi-entorno-php.git mi-proyecto
cd mi-proyecto

# 2. Inician su propio repositorio PHP en www/
cd www
git init  # O clonan su proyecto existente
# git clone https://github.com/usuario/proyecto-php.git .

# 3. Trabajan normalmente
ejecutar el docker-compose para habilitar los contenedores 
docker-compose up -d