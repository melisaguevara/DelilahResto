Bienvenido/a a la API de Delilah Rest�.

A continuaci�n te explicaremos los pasos para inicializar el servidor y la base de datos para poder interactuar con la 
API desde tu propia m�quina. 

En la carpeta encontrar�s __ archivos. 

- Queries base de datos: Posee los queries para que puedas crear la estructura de las tablas 
requeridas para el funcionamiento de la api. Una vez ejecutados, en tu motor de base de datos deber�as tener
una nueva base de datos llamada delilah, con 4 tablas: usuarios, productos, pedidos y pedidos_productos. La tabla usuarios 
deber�a tener un registro, que ser� el que usar�s para las funcionalidades de administrador. Las otras 3 estar�n vac�as.

- serverdelilah.js: es el archivo de la api. 
- package.json: es el archivo que contiene la informaci�n de los m�dulos que deber�s importar para poder usar la api
correctamente.
-documentaci�n.yaml y documentaci�n.html: Son los archivos en los que encuentras las instrucciones de c�mo usar cada uno
de los endpoints correctamente. Los par�metros que espera recibir y lo que obtendr�s como respuesta de cada uno de ellos. 

Ahora veremos como inicializar la API.

1. Lo primero que debes hacer es abrir el archivo serverdelilah. Asegurate que en la terminal tengas abierta la carpeta
en la que se encuentra el archivo.

2. Luego, en la consola, corre el comando npm install. Esto instalar� los m�dulos necesarios para que la api funcione en 
tu compu. (Asegurate de tener node instalado)

3. El siguiente paso es configurar la base de datos para conectarlo con nuestro proyecto. Para eso en la l�nea n�mero
12 del archivo serverdelilah, reemplaza en ("mysql://root:@localhost:3306/delilah") reemplaza el segmento "root:" por tu 
usuario y contrase�a en la base de datos de la siguiente manera --> usuario:contrase�a

4. Y ahora s�lo falta ejecutar el archivo y ya est�s listo para usar la api desde el puerto 3000 de tu computadora,
para empezar a usar la api pod�s crear un nuevo usuario desde el endpoint post usuarios y para probar las funcionalidades
de administrador, ac� te dejamos el usuario y contrase�a necesario para ello:

nombreusuario: delilahAdmin
contrase�a: administrador56

Recuerda que en la documentaci�n ten�s todos los endpoints explicados detalladamente.
