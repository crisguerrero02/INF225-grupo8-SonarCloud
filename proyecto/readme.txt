para la instalacion del proyecto se debe descargar desde los branch "client" y "server" los archivos y ponerlos dentro de una carpeta con los nombres del branch , ambas carpetas deben estar a la misma altura ,
luego entramos por medio de la terminal de a la carpeta client y escribimos el comando "npm fix audit --force" y lo ejecutamos dos veces. Por ultimo se debe cambiar la url de mongoDB que estan dentro de 
server/database/index.js , a su propia base de mongoDB, se considera que ya tiene cuenta de mongoDB
