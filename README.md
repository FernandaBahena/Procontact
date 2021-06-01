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

![Captura de Pantalla 2021-05-31 a la(s) 13 39 41](https://user-images.githubusercontent.com/85090116/120383168-28f1c080-c2ea-11eb-942f-ee4c69520a5d.png)

2.	Realizar un request POST a la URL anterior, y con body:
{
"name":"Tu nombre",
"email":tunombre.tuapellido@procontacto.com.mx
}
Tip: (Marcar la opción “raw” como body)
![image](https://user-images.githubusercontent.com/85090116/120382770-ad900f00-c2e9-11eb-892a-6d1a5a3a5b7d.png)

3.	Realizar nuevamente un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json!

![Ejercicio 3 parte 1](https://user-images.githubusercontent.com/85090116/120257596-22196e00-c256-11eb-9499-454b1e4ce1c0.png)

### EJERCICIO 4 ⌨️

_Cambiar el idioma de Trailhead a inglés.
Realizar los siguientes módulos de Trailhead:
●	Fundamento de la plataforma Salesforce
●	Fundamentos de Apex y .NET
●	Modelado de datos
●	Fundamentos y base de datos de Apex
●	Desencadenadores de Apex
Se recomienda usar el mismo Playground para todos módulos solicitados. Excepto que se solicite crear uno nuevo en el enunciado del Módulo.

Liga Trailhead:
https://trailblazer.me/id/fecevedo


## EJERCICIO 5 📦

_Explicar que son conceptualmente, qué datos almacenan en forma estándar y cómo se relacionan el resto (algunos no se relacionan entre sí) cada uno de los siguientes objetos de Salesforce:_

1.	Lead: Es un usuario que ha entregado sus datos a una empresa y que como consecuencia pasa a ser un registro de su base de datos.
2.	Account: Son compañías con las que hace negocios y los contactos son las personas que trabajan para dichas compañías.
3.	Contact: Son las personas que trabajan con sus cuentas se llaman contactos
4.	Opportunity: Es una serie de etapas vinculadas al tipo de tareas que se realizan, quién tiene la iniciativa y en qué medida es probable que se realice la venta
5.	Product: Son los elementos y servicios que distribuye a clientes. Cada producto puede existir en múltiples listas de precios con precios diferentes.
6.	PriceBook: Las listas de precios rastrean los precios de los productos y servicios que su empresa ofrece a los clientes.
7.	Quote: Es el documento que recoge todo lo anterior, generalmente incluye imagen de marca o marcas, clausulado legal o formato para convertirlo en un contrato o precontrato
8.	Asset: Representa un artículo de valor comercial, como un producto vendido por su empresa o un competidor, que un cliente ha comprado e instalado.
9.	Case: Es una forma sencilla de crear asistencia online. Fundamentalmente, es un formulario de campos de caso que los clientes rellenan y envían a los agentes. 
10.	Article: Muestra los artículos más populares en su sitio.

Los campos enumerarlos a través de una lista de texto en el Readme y las relaciones a través de un diagrama UML simple realizado con Drawio.

![Ferprocontacto](https://user-images.githubusercontent.com/85090116/120245566-3435e500-c233-11eb-8f6b-ea1b48dc5865.png)

## EJERCICIO 6 🛠️

_A.	Consultar tu ID haciendo un GET con POSTMAN a este WS: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json![image]_

![id fernanda](https://user-images.githubusercontent.com/85090116/120258668-19c23280-c258-11eb-8ff4-f8e346b17086.png)

## EJERCICIO 7 🖇️

* **Soluciones de Salesforce**
A.	¿Qué es Salesforce?
Es un software que nos va a ayudar a gestionar todo el flujo de clientes que tenemos en nuestra empresa atraves de la web, ofrece bastante beneficios para empresa y negocios.

B.	¿Qué es Sales Cloud?
Es una aplicación de gestión de relaciones con clientes (CRM) de Salesforce basada en la nube. Incluye herramientas de gestión de contactos, automatización de las ventas, previsión de ventas y productividad. Permite a los usuarios tener acceso a su información donde quiera que se encuentren, siempre y cuando tengan un PC conectado o una aplicación móvil basada en Internet.

C.	¿Qué es Service Cloud?
Es una de las soluciones de software de servicio al cliente mejor calificadas y más populares del mundo. Dicho software de permite que los agentes se conecten con los clientes y solucionen sus problemas rápidamente. Proporciona gestión de casos, acceso al cliente en todos los canales, integración a los sistemas de datos preexistentes, aplicaciones de integración preincorporadas, tickets de asistencia, base de conocimientos, enrutamiento y escalamiento, y gestión de colas.

D.	¿Qué es Health Cloud?
Es una solución de gestión de pacientes y CRM de atención médica basada en la nube que permite la colaboración entre proveedores de atención médica, pagadores y pacientes. El software está basado en la plataforma de CRM de Salesforce y ha sido diseñado específicamente para satisfacer las necesidades del sector de la salud.

E.	¿Qué es Marketing Cloud?
Es una plataforma de Salesforce que pymes y grandes empresas pueden utilizar para invertir en estrategias de email marketing de nivel profesional.El objetivo es comunicarse con las diferentes audiencias y hacerles llegar el mensaje adecuado, con el tono correcto y en el momento perfecto para seducir, convencer y persuadir del uso de tus productos y servicios.

* **Funcionalidades de Salesforce**
A.	¿Qué es un RecordType?
Un tipo de registro nos permiten especificar una categoría de registros que muestran diferentes valores de lista de selección y diseños de página.

B.	¿Qué es un ReportType?
Define el conjunto de registros y campos disponibles para un informe en función de las relaciones entre un objeto principal y sus objetos relacionados. Los informes muestran solo los registros que cumplen los criterios definidos en el tipo de informe.

C.	¿Qué es un Page Layout?
Nos permite personalizar el diseño y organización de detalles y editar páginas de registros en Salesforce.Los diseños de página se pueden utilizar para controlar la apariencia de campos, listas relacionadas y enlaces personalizados en la página de edición y detalle de objetos estándar y personalizados.

D.	¿Qué es un Compact Layout?
Controlan qué campos aparecen en el encabezado. Para cada objeto, puede asignar hasta 10 campos, incluido el campo Nombre, para mostrar en esa área.

E.	¿Qué es un Perfil?
Definen cómo acceden los usuarios a objetos y datos y qué pueden hacer en la aplicación.

F.	¿Qué es un Rol?
Controlan el nivel de visibilidad que un usuario tiene sobre los datos de su organización. A los usuarios que requieren visibilidad a toda la organización debe asignárseles el nivel más alto en la jerarquía, por ejemplo, personal ejecutivo.

G.	¿Qué es un Validation Rule?
Verifican que los datos ingresados por usuarios en registros cumplen los estándares que especifica antes de poder guardarlos. Una regla de validación puede contener una fórmula o expresión que evalúa los datos en uno o más campos y ofrece un valor “Verdadero” o “Falso”.

H.	¿Qué diferencia hay entre una relación Master Detail y Lookup?
Master Detail: 
• Uno: muchas relaciones.
• Muchas - muchas relaciones.
Lookup:
• Auto búsqueda.
• Búsqueda externa

I.	¿Qué es un Sandbox?
Es una copia de Producción, en donde podemos realizar todos los cambios que queramos a la configuración y hacer testeos, sin molestar a los usuarios. Existen 4 tipos desarrollador, desarrollador pro, parcial y completo.

J.	¿Que es un ChangeSet?
Es una manera de enviar información sobre personalizaciones desde una organización a otra. 

K.	¿Para qué sirve el import Wizard de Salesforce?
Permite importar datos en objetos estándar comunes, como contactos, clientes potenciales, cuentas, así como datos en objetos personalizados. Puede importar hasta 50.000 registros a la vez. Proporciona una interfaz simple para especificar los parámetros de configuración, las fuentes de datos y las asignaciones de campos que asignan los nombres de los campos en su archivo de importación con los nombres de los campos en Salesforce.

L.	¿Para qué sirve la funcionalidad Web to Lead?
Permite diseñar un formulario incluyendo las preguntas más adecuadas para cada tipo de negocio con el objetivo de insertarlo en un blog o una web corporativa, automatizando así la captación de leads y la integración de los datos de los usuarios en el CRM

M.	¿Para qué sirve la funcionalidad Web to Case?
Es una herramienta a través de la cual puede publicar una página web simple y aleatoria que permite a sus clientes. Para enviar un caso directamente a su instancia de Salesforce.como, ofrece a los usuarios una forma de recopilar información en un formato más específico.

N.	¿Para qué sirve la funcionalidad Omnichannel?
envía el trabajo a los agentes en tiempo real, directamente desde la consola de Salesforce. Omni-Channel hace que todo suceda utilizando objetos, que es solo una palabra elegante para cualquier cosa que pueda ser enrutada a sus agentes. 

O.	¿Para qué sirve la funcionalidad Chatter?
Permiten a los usuarios colaborar, ser más receptivos y obtener toda la información que necesitan rápidamente. Esta función tiene la capacidad de configurar varios grupos que se centran en diversos temas.

* **Conceptos generales**
A.	¿Qué significa SaaS? ¿Salesforce es Saas?
Es un modelo de prestación de software basado en la nube, en el cual el proveedor de nube desarrolla y mantiene un software de aplicaciones de nube, proporciona actualizaciones de software automáticas y hace que el software sea accesible para los clientes a través de internet. En salesforce es una forma de disponibilizar softwares y soluciones de tecnología por medio de la internet, como un servicio. Con ese modelo, su empresa no necesita instalar, mantener y actualizar hardwares y softwares. El acceso es fácil y simples: solo es necesario conexión con la internet.

B.	¿Que significa que una solución sea Cloud?
Es una tecnología que permite acceso remoto a softwares, almacenamiento de archivos y procesamiento de datos por medio de Internet, siendo así, una alternativa a la ejecución en una computadora personal o servidor local.

C.	¿Que significa que una solución sea On-Premise?
Aquellos sistemas que son instalados en la propia empresa. Se trata de tener en “Casa” los servidores y el software que proporcionan un determinado servicio para la actividad desarrollada.

D.	¿Que es un pipeline de ventas?
Es el mapa de las actividades diarias que componen el proceso de ventas en el trabajo de un representante comercial, mostrando cada una de las etapas de una negociación.

E.	¿Que es un funnel de ventas?
Representa todo el proceso de cierre de un negocio, desde el momento de la captación hasta la conversión final.

F.	¿Qué significa Customer Experience?
significa preocuparse por la experiencia de un extremo a otro que su marca tiene con sus prospectos, clientes y evangelistas de la marca. La gestión de la experiencia del cliente requiere prestar atención a los detalles en todos los pasos del proceso de compra, desde el contenido creado para captar el conocimiento, hasta la experiencia de comercio electrónico de las compras en su sitio y el compromiso posventa de mantener a los clientes leales comprometidos mediante boletines informativos y cupones y ventas de agradecimiento al cliente.

G.	¿Qué significa omnicanalidad?
Ofrecer una experiencia de cliente fluida en distintos canales integrándolos en un único sistema. De esta manera, los agentes del servicio de atención al cliente tienen una visión completa de las interacciones de un cliente, lo que les permite responder a las consultas de forma más eficiente y eficaz.

H.	¿Qué significa que un negocio sea B2B?
B2B es una estrategia de venta en la que se da un intercambio comercial de productos o servicios, entre dos o más empresas.

I.	¿Qué significa que un negocio sea B2C?
actividad comercial entre un negocio y un consumidor individual. Mientras esto aplica a cualquier tipo de negocio de venta directa al consumidor, se ha asociado con la venta en línea, también conocido como e-commerce.

J.	¿Qué es un KPI?
Es una serie de métricas que se utilizan para sintetizar la información sobre la eficacia y productividad de las acciones que se lleven a cabo en un negocio con el fin de poder tomar decisiones y determinar aquellas que han sido más efectivas a la hora de cumplir con los objetivos marcados en un proceso o proyecto concreto.

K.	¿Qué es una API y en qué se diferencia de una Rest API?
Es un conjunto de definiciones y protocolos que se utiliza para desarrollar e integrar el software de las aplicaciones. API significa interfaz de programación de aplicaciones. Api rest es el conjunto de buenas prácticas utilizadas en las requisiciones HTTP realizadas por una API en una aplicación web. 

L.	¿Qué es un Proceso Batch?
Es el proceso mediante el cual una computadora completa lotes de trabajos, a menudo simultáneamente, en orden secuencial y sin parar. También es un comando que garantiza que los trabajos grandes se calculen en partes pequeñas, para mejorar la eficiencia durante el proceso de depuración.

M.	¿Qué es Kanban?
Es un método visual que se utiliza para controlar las tareas a través de su división por fases hasta su finalización. Actualmente este método ha pasado a formar parte de las conocidas como metodologías ágiles, las cuales tratan de gestionar el trabajo y adaptarlo a las condiciones de los proyectos.

N.	¿Qué es un ERP? ¿Salesforce es un ERP?
Es un conjunto de sistemas de información que permite la integración de ciertas operaciones de una empresa, especialmente las que tienen que ver con la producción, la logística, el inventario, los envíos y la contabilidad. Salesforce es un ERP ya que la gran mayoría de sus productos están enfocados a aumentar considerablemente su producción y las ventas. Esto se lleva a cabo a través de una ágil gestión de procesos internos y cuya principal herramienta es el CRM.


## Autores ✒️

_Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios_

* **Fernanda Bahena Acevedo** - *Trabajo Inicial* - [villanuevand](https://github.com/villanuevand)

## Expresiones de Gratitud 🎁

* Comenta a otros sobre este proyecto 📢
* Invita una cerveza 🍺 o un café ☕ a alguien del equipo. 
* Gracias por la oportunidad 🤓.

