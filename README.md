Abrimos PowerShell para verificar la version de docker para trabajar: docker --version
Descargamos la imagen oficial de Nginx con el siguiente comando:  docker pull nginx
Para levantar la imagen usamos: docker build -t nginx
Hacemos correr Nginx: docker run --name web -d -p 8080:80 nginx
Para confirmar que el contenedor se ha levantado usamos: docker ps
Verificamos que nginx este corriendo de manera local a traves de localhost
Iniciamos sesion en nuestra cuenta de GitHub
Creamos un nuevo Repositorio para la pregunta 1
Iniciamos git init
Añadimos nuestro primer commit: git commit -m "first commit"
Cambiamos el nombre git branch -M main
Añadimos la carpeta que creamos git remote add origin https://github.com/SeanNina/ExamenFinal-Pregunta1.git
Teminamos con un git push
Despues trabajamos en Visual Code para crear la pagina web
Creamos una carpeta en HTML Y CSS
Desarrollamos una pagina web con imagenes de los 9 departamentos de Bolivia
Subimos toda la carpeta de la pagina web como second commit a nuestro repositorio
Agregamos nuestro segundo commit: cd C:\Users\Vic_S\Desktop\Ej1\Pagina Web
Usamos el comando git add .
Usamos la direccion de nuestra carpeta: git commit -m "second commit - C:\Users\Vic_S\Desktop\Ej1\Pagina Web"
Terminamos con "git push" para subir nuestro trabajo a GitHub
