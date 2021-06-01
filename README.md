# Procontact
Desarollo de proyecto procontacto
# Título del Proyecto

_Evaluación práctica procontacto_

## Desarollo 🚀

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._

Mira **Deployment** para conocer como desplegar el proyecto.


### Pre-requisitos 📋

_Que cosas necesitas para instalar el software y como instalarlas_

```
Da un ejemplo
```

### Instalación 🔧

_1.Instalar el IDE Visual Studio Code_
> [Visual Studio Code](https://code.visualstudio.com/) Es una aplicación que nos brinda facilidades al momento de generar código. Dentro de Pro Contacto utilizamos Visual Studio Code para los proyectos relacionados a aplicaciones web y mobile. El mismo permite trabajar con varios lenguajes tales como: HTML, CSS, C#, Javascript, APEX (NodeJS, Angular, IONIC, React, Typescript, etc).


_2. Instalar GIT y GIT Bash_
> [Git] (http://windows.github.com.) Git es una aplicación utilizada para el control de versionado de código. En otras palabras, es una suerte de “disco” en donde se guardarán los distintos files que componen nuestra aplicación (ejemplo: index.html, estilos.css, etc). La gran ventaja de GIT es que al momento de subir una versión nueva de un archivo, genera un “backup” de la versión anterior para poder ser restaurado cuando se desee. Además, el código se encuentra en la “nube”, por lo que puede ser accedido y descargado desde cualquier lugar que tenga acceso a internet.

## EJERCICIO 2 ⚙️

_Las siguientes preguntas están orientadas a la comprensión del protocolo HTTP. Son agnósticas al lenguaje de programación, la idea es comprender los conceptos del estándar:_

1.	¿Qué es un servidor HTTP? 
Es el servidor que almacena los documentos que componen una página web y puede ser dinámico o estático. 

2.	¿Qué son los verbos HTTP? Mencionar los más conocidos
Sirven para decir el tipo de acción que se quiere utilizar con un recurso, puede ser GET, HEAD, PUT, DELETE, TRACE, CONNECT, OPTIONS, POST que son los más populares.

3.	¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers? 
-	Request permite enviar todo tipo de petición HTTP  a un URL especifico y procesar la respuesta.
-	Response es el mensaje que envía el servidor al cliente tras haber recibido una petición o HTTP request.

4.	¿Qué es un queryString? (En el contexto de una url)
Es la parte de una URL que contiene lo datos que debemos pasar a aplicaciones web como los programas CGI.

5.	¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?
Son los valores de estado numérico para las solicitudes HTTP, (las secciones de datos de los mensajes de error, reenvío y respuestas de re direccionamiento).

6.	¿Cómo se envía data en un Get y cómo en un POST? 
-	Con el método GET, los datos que se envían al servidor se escriben en la misma dirección URL.
-	El método POST introduce los parámetros en la solicitud HTTP para el servidor. Por ello, no quedan visibles para el usuario. Además, la capacidad del método POST es ilimitada.

7.	¿Qué verbo http utiliza el navegador cuando accedemos a una página?
Referer: contiene la URL de la página que le ha dado acceso a la que está
solicitando.

8.	Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.
JSON: es un formato ligero de intercambio de datos, que resulta sencillo de leer y escribir para los programadores y simple de interpretar y generar para las máquinas. XML: es uno de los formatos más utilizados para el intercambio de información entre sistemas. El formato de este estándar está basado en texto para representar información estructurada: datos, documentos, configuración, etc..

9.	Explicar brevemente el estándar SOAP
Es un estándar basado en XML para la transmisión de mensajes en HTTP y otros protocolos de Internet. Es un protocolo ligero para el intercambio de información en un entorno descentralizado y distribuido.

10.	Explicar brevemente el estándar REST Full
Es un conjunto de principios y patrones de comunicación que ayudan a crear una forma de pensar y construir las APIs. Este tipo de arquitectura se define por un conjunto de restricciones entre los elementos, componentes, conectores y datos usados.

11.	¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?
-	Headers son la parte central de los HTTP requests y responses, y transmiten información acerca del navegador del cliente, de la página solicitada, del servidor, etc. La primera línea es la línea del request, que contiene su información básica (método HTTP, URL y versión).
-	Content-Type es la propiedad de cabecera (header) usada para indicar el media type (en-US) del recurso. Content-Type dice al cliente que tipo de contenido será retornado.

### EJERCICIO 3 🔩

_Recomendamos previamente entender los conceptos de la sintaxis “json” antes de arrancar con los ejercicios.
Descargar el POSTMAN (aplicación para realizar request como cliente), adjuntando un screen de resolución para cada ítem:_

Realizar un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json


### Y las pruebas de estilo de codificación ⌨️

_Explica que verifican estas pruebas y por qué_

```
Da un ejemplo
```

## Despliegue 📦

_Agrega notas adicionales sobre como hacer deploy_

## Construido con 🛠️

_Menciona las herramientas que utilizaste para crear tu proyecto_

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - El framework web usado
* [Maven](https://maven.apache.org/) - Manejador de dependencias
* [ROME](https://rometools.github.io/rome/) - Usado para generar RSS

## Contribuyendo 🖇️

Por favor lee el [CONTRIBUTING.md](https://gist.github.com/villanuevand/xxxxxx) para detalles de nuestro código de conducta, y el proceso para enviarnos pull requests.

## Wiki 📖

Puedes encontrar mucho más de cómo utilizar este proyecto en nuestra [Wiki](https://github.com/tu/proyecto/wiki)

## Versionado 📌

Usamos [SemVer](http://semver.org/) para el versionado. Para todas las versiones disponibles, mira los [tags en este repositorio](https://github.com/tu/proyecto/tags).

## Autores ✒️

_Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios_

* **Andrés Villanueva** - *Trabajo Inicial* - [villanuevand](https://github.com/villanuevand)
* **Fulanito Detal** - *Documentación* - [fulanitodetal](#fulanito-de-tal)

También puedes mirar la lista de todos los [contribuyentes](https://github.com/your/project/contributors) quíenes han participado en este proyecto. 

## Licencia 📄

Este proyecto está bajo la Licencia (Tu Licencia) - mira el archivo [LICENSE.md](LICENSE.md) para detalles

## Expresiones de Gratitud 🎁

* Comenta a otros sobre este proyecto 📢
* Invita una cerveza 🍺 o un café ☕ a alguien del equipo. 
* Da las gracias públicamente 🤓.
* etc.
