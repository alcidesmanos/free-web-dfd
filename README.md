# free-web-dfd
Diseñador de diagramas de flujos de datos en interface WEB.

Permitira su diseño, ejecución, guardar en JSON, importar JSON y DFD, imprimir

Cuando estudie algoritmia fue muy duro para mi entender las estructuras de datos, probarlas y testearlas, hasta que conoci el programa freedfd

https://github.com/arhuaco/freedfd

El cual me ayudo muchisimo a aprender a realizar algoritmos!!

Ya han pasado un poco más 18 años desde su creación, y como ya tiene mayoria de edad, es hora que se reproduzca!! :D

Tengo la fortuna de conocer a sus autores pues estudiamos en la super mega hiper Universidad del Magdalena de Santa Marta, Colombia.

Saludes a Ellos : Nelson, Eduardo y Fabian ... aunque no se si todos ellos me recuerden :D 


Se publicaran fuentes a medida que las tenga testeadas y documentadas.

Yo trabajo en java, pero como es algoritmia , los convertidores se pueden trabajar en otros lenguajes abriendo una sección para ellos.

Requerimientos para java.
Eclipse o Netbeans con el plugin de Gradle instalado

Librerias de terceros
Definidas en el archivo gradle , en general jdom, json, slf4j

Como homenaje a freedfd, quize antes de todo ser capaz de cargar y graficar un archivo DFD diseñado en ella,
en la aplicación WEB que esta en desarrollo.

Lo primero que se analizo es la forma como freedfd almacena los archivos .dfd, 
como no hay una documentación del tema se uso el codigo fuente como insumo.

De este analisis surge el primer migrador, a formato XML, con nombres de etiquetas dicientes,
que permiten entender un poco mas la estructura del algoritmo leyendo el archivo, 
pero soló el archivo no es suficiente, es necesario definir un schema para establecer una documentación seria 
para los que quieran trabajar la rama XML.

Despúes de trabajar aplicaciones WEB con javascript, trabajar una definición con XML no resulto mucho de mi agrado,
así que procedi a una definición en JSON igual, seria muy bueno definir este formato en un estandar para su documentación y validación.
http://json-schema.org/

Se publicaran inicialmente se publicaran imagenes del diseño y  JSON generados para sus observaciones y comentarios.
para hacer los ajustes y publicar la version beta, definitiva para arrancar el proyecto.

ASI: 
samples/dfd
samples/json

Se cancela trabajo con XML, para tener un alcance mas corto.

y contendran los archivos definidos en el proyecto freedfd migrados
