##Proyecto Final de asignatura. [![Build Status](https://travis-ci.org/alu0100693737/Proyecto-PL.svg?branch=master)](https://travis-ci.org/alu0100693737/Proyecto-PL)
##Procesadores de Lenguaje.
##Iván García Campos  

* Descripcion:
Ejecutar aplicacion: node --harmony_destructuring app.js

* Proyecto c9: https://ide.c9.io/alu0100693737/proyectopl
* Pag web en C9: https://proyectopl-alu0100693737.c9users.io/?
* Pag web en Heroku: https://still-basin-93201.herokuapp.com/
* Pag Test en Heroku: https://still-basin-93201.herokuapp.com/test/
* Pag personal de Usuario: http://alu0100693737.github.io/

### Descripcion
Se ha utilizado **Node.js, expressjs**. La aplicacion esta desarrollada para **heroku y para cloud9** con el uso de **Mongo y Mongoose** permitiendo un máximo de 3 ficheros y posibilidad de guardar indicando un nombre con extension .pl0.

La aplicación tiene **localStorage, utiliza Sass, Ecmas6, karma, travis y gulpfile.**
Se han desarrollado pruebas mediante **mocha y chai**, incluyendo test de tipo bdd e incorporando una vista test.ejs. Se ha agregado ademáws, **blanket** para cubrimiento de código.

En cuanto al pegjs, se han incorporado el **tipo for de la forma: for(i = 0; i < 5; i+1), los string delimitados por " ", y  los comentarios de cabecera que empiezan por \\\\. En la semantica se ha creado la tabla de simbolos, definido la relacion padre hijo y recorrido en preorden. La aplicacion muestra la tabla de simbolos al final del analisis.**

* Crear base de datos mongo:
* $ mkdir data
* $ echo 'mongod --bind_ip=$IP --dbpath=data --nojournal --rest "$@"' > mongod
* $ chmod a+x mongod

You can start mongodb by running the mongod script on your project root:
* $ ./mongod

