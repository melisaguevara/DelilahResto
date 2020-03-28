Bienvenido/a a la API de Delilah Restó.

A continuación te explicaremos los pasos para inicializar el servidor y la base de datos para poder interactuar con la 
API desde tu propia máquina. 

En la carpeta encontrarás __ archivos. 

- Queries base de datos: Posee los queries para que puedas crear la estructura de las tablas 
requeridas para el funcionamiento de la api. Una vez ejecutados, en tu motor de base de datos deberías tener
una nueva base de datos llamada delilah, con 4 tablas: usuarios, productos, pedidos y pedidos_productos. La tabla usuarios 
debería tener un registro, que será el que usarás para las funcionalidades de administrador. Las otras 3 estarán vacías.

- serverdelilah.js: es el archivo de la api. 
- package.json: es el archivo que contiene la información de los módulos que deberás importar para poder usar la api
correctamente.
-documentación.yaml y documentación.html: Son los archivos en los que encuentras las instrucciones de cómo usar cada uno
de los endpoints correctamente. Los parámetros que espera recibir y lo que obtendrás como respuesta de cada uno de ellos. 

Ahora veremos como inicializar la API.

1. Lo primero que debes hacer es abrir el archivo serverdelilah. Asegurate que en la terminal tengas abierta la carpeta
en la que se encuentra el archivo.

2. Luego, en la consola, corre el comando npm install. Esto instalará los módulos necesarios para que la api funcione en 
tu compu. (Asegurate de tener node instalado)

3. El siguiente paso es configurar la base de datos para conectarlo con nuestro proyecto. Para eso en la línea número
12 del archivo serverdelilah, reemplaza en ("mysql://root:@localhost:3306/delilah") reemplaza el segmento "root:" por tu 
usuario y contraseña en la base de datos de la siguiente manera --> usuario:contraseña

4. Y ahora sólo falta ejecutar el archivo y ya estás listo para usar la api desde el puerto 3000 de tu computadora,
para empezar a usar la api podés crear un nuevo usuario desde el endpoint post usuarios y para probar las funcionalidades
de administrador, acá te dejamos el usuario y contraseña necesario para ello:

nombreusuario: delilahAdmin
contraseña: administrador56

Recuerda que en la documentación tenés todos los endpoints explicados detalladamente.
