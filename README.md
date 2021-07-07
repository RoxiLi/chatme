# CHATME

Permite dejar mensajes que persiste según la validación del usuario, admitidos  'admin' y 'invitado'
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





