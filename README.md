# BASDE_DATOS
codigo para el proyecto final de base de datos 
En el presente github presentaremos la generacion de un aplicativo web q nos ayudara a demostrar el funcionamiento de una base de datos por medio de php, css y sobre todo sql
el siguiente link es una guia practica para seguir con la creacion de la misma:
# https://www.youtube.com/watch?v=IZHBMwGIAoI
para ello tendran que descargar la siguiente app: XAMPP el cual es un servidor q nos permitira conectar el html con el sql
lo descargan de su pagina web: https://www.apachefriends.org/es/index.html
finalmente les dejo los comandos para que lo corran:

cd ~/Descargas para entrar a descargas

chmod +x xampp-linux-x64-8.2.12-0-installer.run para descomprimir el programa

sudo ./xampp-linux-x64-8.2.12-0-installer.run para ejecutar la instalacion del programa

por si acaso tambien ejecuten el siguiente comando:

sudo apt install net-tools para descargar net.tools ya q lo necesitamos

sudo /opt/lampp/lampp start para comenzar la ejecucion del programa

sudo /opt/lampp/lampp status para evicdenciar si todo esta funcionando, en caso de que no este funcionando MySQL, ingresar el siguiente comando

sudo /opt/lampp/lampp startmysql para inicializar el funcionamiento del MySQL

Una ves instalado se van a la carpeta de XAMPP, encontraran dentro una carpeta llamada htdocs, dentro de esa carpeta copian la carpeta que se subio al repositorio
y continuan en el minuto 52:37, si es de ayuda revisan todo el video para q comprendan mas.

# Comandos HTML para la pagina por el momento:
http://localhost/sitioweb/administrador/inicio.php este para entrar a la parte de administracion de la pagina

http://localhost/sitioweb/ para entrar al sitio que todo usuario presenciara

luego de esto ya solo falta la interaccion con los botones generados en cada sitio
