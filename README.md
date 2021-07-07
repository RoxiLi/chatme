# CHATME

Permite dejar mensajes que persiste según la validación del usuario. Admitidos  `admin` y `invitado`, deben ser digitados tal cual se muestra.
TECNOLOGÍAS
* [FRONTEND](https://github.com/RoxiLi/message-frontend/tree/master) `ANGULAR` 
* [BACKEND](https://github.com/RoxiLi/message-backend) `NODE.JS` 
* [BASE DE DATOS](https://www.mongodb.com/es) `MONGODB ATLAS` 

## BACKEND
### ARQUITECTURA
Contiene dos componentes user y message
<br>
 <img  height="460px"  width="560px"  style="float: left;"  src="https://github.com/RoxiLi/chatme/blob/master/assets/arquitectura-nodejs.jpg"  alt="Vex Logo"> 
 
  En el archivo `.env`  , se pueden cambiar las configuraciones y adecuarlo al entorno deseado sustituyendo los siguientes datos
 
 ````
 // url de la conexión con mongo
DB_CONNECT =
// Puerto de escucha
PORT =
// direccion del host por defecto 'http:localhost'
HOST =
// Por defecto 'app'
PUBLIC_ROUTE =
````

## FRONTEND
### Estructura
Dentro de la carpeta src/app
* Models
* Services
* Modules

En la carpeta services src/enviroments se encuenta  `enviroment.ts`:
 ````
 // direccion host + puerto
 baseUrl: '';
````
Se debe cambiar por la del entorno que se despliegue por defecto 'http://localhost:3000'

## BASE DE DATOS
La database cuenta con mis credenciales pero la url genérica es la de abajo seleccionada para el drive Node.js y versión 2.2.12 or later y se puede reemplazar en el backend en `DB_CONNECT`

 ````
mongodb://db_user:<password>@cluster0-shard-00-00.isyfp.mongodb.net:27017,cluster0-shard-00-01.isyfp.mongodb.net:27017,cluster0-shard-00-02.isyfp.mongodb.net:27017/myFirstDatabase?ssl=true&replicaSet=atlas-14jx4l-shard-0&authSource=admin&retryWrites=true&w=majority
````

Replace <password> with the password for the db_user user. Replace myFirstDatabase with the name of the database that connections will use by default. Ensure any option params are URL encoded.




