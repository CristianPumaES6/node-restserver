####
Ejecutar con ?> node server/server.js

npm bodyparse < req.body > la vida se nos hace mas facil.

sudo mongod desde terminal. < habilitar mongo >

instalar mongo sh

variable de entorno en heroku.

Crear variable de entorno en heroku
heroku config:set MONGO_URI="wwwdasdafas as dsa " 

mongodb://<usersinpuntos>:<contrasela>.@ds163254.mlab.com:63254/udemy-cafe


 process.env.SEED 


 typeScript 

let resp = pm.response.json();

if( resp.ok ){
    let token = resp.token;
    pm.environment.set("token",token);
} else {
    console.log("No se actualizo el token.");
}