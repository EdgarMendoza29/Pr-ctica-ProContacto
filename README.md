![Imagen1](https://user-images.githubusercontent.com/111367485/203929728-aee26d03-1e69-4df2-b5b7-a3228a18a40f.png) 

# Evaluación Práctica 

## Ejercicio 2

1. ¿Qué es un servidor HTTP?

    HTTP o también llamado protocolo de transferencia de hipertexto, es el protocolo de red que permite la transferencia de documentos de hipermedia en la red, entre un navegador y la red, para que los usuarios puedan leerlo. 

    Un servidor HTTP es una pieza de software, la cual es capaz de comprender direcciónes web (URLs) y HTTP. Este servidor HTTP puede ser accedido a través de los nombres de dominio de sitios web que contiene, y luego transfiere la información o contenido de esos sitios web al dispositivo del usuario.

2. ¿Qué son los verbos HTTP?

    - Get: Get solicita una representación de un recurso en específico, este método busca recuperar datos.
    - Head: Pide una respuesta idéntica a Get, pero sin el cuerpo de la respuesta.
    - Post: Es un método de creación, añade datos al servidor. Causa a menudo cambios en el estado del servidor.
    - Put: Es utilizada para reemplazar la información.
    - Delete: Este método borra un recurso en específico.   
    - Connect: El método establece un túnel hacia un servidor identificado por el recurso.
    - Options: Options es utilizado para describir las opciones de comunicación para el destino.
    - Trace: Es un método que devolverá la información que se ha enviado en la solicitud, creando una especie de bucle de retorno de mensaje.
    - Patch: Este método es utilizado para aplicar modificaciones parciales en un recurso en específico.

3. ¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?

    Request son peticiones enviadas por el usuario para iniciar una acción en el servidor. Mientras que el response hace referencia a la respuesta por parte del servidor. 
    
    Los headers permiten al usuario enviar información adicional junto a una petición o respuesta.

4. ¿Qué es un queryString?

    Es un término utilizado para hacer referencia a una interacción con una base de datos. Es la parte de URL que contiene los datos que deben pasar por la web.

5. ¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?

    Un responseCode es un código que se envía en respuesta a un encabezado de solicitud de upgrade del cliente e indica que el servidor acepta el cambio de protocolo propuesto por el agente de usuario.

    Uno de las posibles causas por lo que los valores son devueltos, es que se tenga un código 403 el cual significa prohibido, lo que significa que el servidor web entiende la solicitud pero no es posible proporcionar un acceso.

6. ¿Cómo se envía la data en un Get y cómo en un POST?

    El método Get envía la información codificada de usuario en el header del HTTP request, directamente en la URL. La página web y la información codificada se separan por un interrogante “?”. Al momento de presionar submit, se envía la información a la página.

    En cuanto al método Post, también se codifica la información, pero esta es enviada a través del body de HTTP Request, por lo que no aparece el URL. La información se envía de manera que no se pueda ver, pues se encuentra en segundo plano u ocultos.

7. ¿Qué verbo http utiliza el navegador cuando accedemos a una página?

    El verbo que se utiliza es u Get, el cual solicita al servidor un archivo; posteriormente el servidor responde enviando un código perteneciente a ese archivo y finalmente lo descifra el navegador.

8. Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles. 

    JSON es un lenguaje usado para el intercambio de datos entre sistemas, está basado en la notación de Javascript. Sirve para la comunicación entre servicios web y los clientes, enviando y recibiendo información en formato JSON.

    ![Jordan](https://user-images.githubusercontent.com/111367485/203920284-41a69e82-75a6-424d-bd02-2b38e63fb573.png)
    
    - Los archivos JSON que representan objetos comienzan con una llave al inicio y terminan con la llave de cierre.
    - Los que representan una lista de valores comienzan con un [ y terminan con ].
    - Siempre se debe usar comillas dobles a la hora de encerrar cadenas y nombres de los atributos del objeto.
    - Cada elemento se separa del siguiente con una coma. Pero no debe de haber una coma después del último elemento en ningún caso.
    
    En cuanto a XML es un formato que se utiliza para almacenar e intercambiar datos estructurados, ya sea documentos, configuraciones, transacciones o simplemente datos.

    ![Captura](https://user-images.githubusercontent.com/111367485/203920920-446beb6b-185d-4547-a975-50f317e34a8a.PNG)
  
    - Los elementos de un documento XML deben seguir una estructura de “Árbol” que es estrictamente jerárquica.
    - Los elementos deben estar correctamente alineados.
    - Los elementos no se pueden superponer entre ellos.
    - Solo puede existir un elemento raíz, en el que estén contenidos los demás.

9. Explicar brevemente el estándar SOAP

    Es un protocolo ligero para el intercambio de información en entornos descentralizados y distribuidos. Los mensajes SOAP se pueden combinar para crear patrones de petición/respuesta.

    Soap es independiente del transporte pero por lo regular es a través de HTTP para ejecutarse con la infraestructura de internet existente. SOAP habilita el enlace y la utilización de servicios Web descubiertos definiendo vía de acceso de mensajes para direccionar mensajes. De igual forma SOAP es un protocolo basado en XML que define tres partes en todos los mensajes:

    - Sobre: El sobre define la infraestructura para describir que hay en un mensaje y cómo procesarlo.
    - Reglas de codificación: El conjunto de reglas de codificación expresa instancias de tipos de datos definidos por la aplicación. SOAP define un esquema de datos que es independiente del lenguaje de programación basado en XSD y normas de codificación para todos los tipos de datos definidos de acuerdo al modelo.
    - Estilos de comunicación: Las comunicaciones pueden tener un formato RPC, el cual invoca una operación que devuelve el resultado; normalmente se utiliza con la codificación SOAP. Por otro lado, también puede ser estilo documento, lo cual proporciona una capa más baja de abstracción y necesita más trabajo de programación.

10.	Explicar brevemente el estándar RESTFul

    Rest es considerado una técnica de arquitectura de software, es decir, un conjunto de principios y patrones de comunicación que ayudan a crear una forma de pensar y construir APIs. Esta se define por un conjunto de restricciones entre los elementos, componentes, conectores y datos usados. 

    RESTful, no es nada más que la implementación de dicha arquitectura. Esta arquitectura al trabajar sobre el protocolo HTTP, los métodos son los mismos que HTTP.
    
11. ¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header? 

    Los headers son la parte central del HTTP requests y transmiten información acerca del navegador del cliente, de la página solicitada. De igual forma dan información adicional sobre el servidor, que no tienen espacio en la línea de estado.

    De igual forma Content-type es utilizado para indicar el tipo de medio original del recurso.
    
  
## Ejercicio 3

1. Request GET:

    ![Captura](https://user-images.githubusercontent.com/111367485/203923895-e9511c9b-f81a-490f-bc20-0dbabe48b0f8.PNG)

2. Request POST:

    ![Captura](https://user-images.githubusercontent.com/111367485/203924353-31a9a259-5b5d-413b-a6e3-3bc1104a6a93.PNG)
    
3. Nuevo Request GET:

    ![Captura](https://user-images.githubusercontent.com/111367485/203924574-0cac19e9-3076-4746-941b-281421d12b8d.PNG)
    
4. ¿Qué diferencias se observan entre las llamadas el punto 1 y 3?

    La diferencia es que en el punto numero 1, arroja una base de datos original. En el punto 2, el POST lo que hizo fue agregar la información de nombre y email, para luego arrojarme una serie de caracteres que es una especie de “número de cuenta” que me identifica. Por último, en el punto 3 se puede observar mi información ya añadida a la base de datos. 

  
## Ejercicio 4

[Perfil de Trailhead](https://trailblazer.me/id/emendoza75)


## Ejercicio 5 


## Ejercicio 6

### Soluciones de Salesforce
  
1. ¿Qué es Salesforce?
    
    Es una plataforma CRM diseñada para reunir, en una única solución, todos los procesos relacionados con los clientes.

2. ¿Qué es Sales Cloud?

    Es un software de ventas de Salesforce que da seguimiento al proceso de ventas, desde perfilar prospectos, hacer el contacto inicial hasta el final de la compra.

3. ¿Qué es Service Cloud?

    Es una aplicación implantada directamente en Salesforce CRM, lo que nos permite dar una atención a cliente completa a cualquier hora y cualquier lugar, ya sea por teléfono, correo, redes sociales, chat, páginas etc.

4. ¿Qué es Health Cloud?

    Es una plataforma diseñada especialmente para la gestión clínica de pacientes por medio de tecnologías on-cloud.

5. ¿Qué es Marketing Cloud?

    Es una plataforma de Salesforce que todo tipo de empresas pueden utilizar para invertir o realizar estrategias de email marketing a nivel profesional.
    
### Funcionalidades de Salesforce

1. ¿Qué es un RecordType?

    Es una funcionalidad de Salesforce que nos permiten definir diferentes business process, pages, pages layouts y picklist values en un objeto en específico.

2. ¿Qué es un ReportType?

    Define el conjunto de registros y campos disponibles para un informe en función de las relaciones entre un objeto principal y relacionados.

3. ¿Qué es un Page Layout?

    Es una función que nos permite personalizar el diseño y la organización de las páginas de detalle y edición de los registros en Salesforce. Estos pueden ser utilizados para controlar la apariencia de los campos, enlaces personalizados etc.

4. ¿Qué es un Compact Layout?

    Son los encargados de controlar qué campos son los que aparecen en los encabezados.

5. ¿Qué es un Perfil?

    Muestra la información detallada acerca del usuario. De igual forma definen como acceden los usuarios a objetos, datos y que es lo que pueden hacer en la aplicación.

6. ¿Qué es un Rol?

    Son los que controlan el nivel de visibilidad que tiene el usuario sobre los datos de la organización y de igual forma puede limitarse a ciertas funciones por la jerarquía de roles.

7.  ¿Qué es un Validation Rule?

    Son las encargadas de verificar que los datos de usuario que se introducen en un registro, cumplan con las normas que especifica antes de que el usuario guarde el registro.

8. ¿Qué diferencia hay entre una relación Master Detail y Lookup?

    Una diferencia es que Master Detail tiene una dependencia directa entre los dos objetos, una relación padre-hijo. Mientras que en lookup no crea una dependencia, sino solamente los relaciona. Otra diferencia es que Master Detail está limitada a 2 relaciones, mientras que Lookup se encuentra limitada a 40.

9. ¿Qué es un Sandbox?

    Es una máquina virtual que cumple con la función de un entorno de pruebas, ya que se encuentra aislado del resto del sistema operativo. En este sistema se pueden ejecutar códigos de software potencialmente inseguros sin afectar a los demás recursos.

10. ¿Qué es un ChangeSet?

    Es una función que permite transferir cambios de un entorno de salesforce a otro. Los cambios están formados por personalizaciones, funciones y componentes que van juntos.

11. ¿Para qué sirve el import Wizard de Salesforce?
    
    Sirve para importar un máximo de 50,000 registros.

12. ¿Para qué sirve la funcionalidad Web to Lead?

    Permite diseñar un formulario incluyendo las preguntas más adecuadas para cada tipo de negocio con el fin de incorporarlo en una web corporativa y de esta manera es posible automatizar las lead y la integración de datos de los usuarios en el CRM.

13. ¿Para qué sirve la funcionalidad Web to Case?

    Es una función que ayuda a recopilar las solicitudes de asistencia de los clientes directamente desde el sitio web de su empresa y a generar automáticamente hasta 5,000 nuevos casos por día.
 
14. ¿Para qué sirve la funcionalidad Omnichannel?

    Es una función personalizable y flexible que se puede configurar sin la necesidad de escribir código. Esta función ayuda a encontrar el camino adecuado hacia los clientes potenciales o casos de trabajo para los agentes.

15. ¿Para qué sirve la funcionalidad Chatter?

    Es una función que permite trabajar juntos, comunicarse y compartir información  a los usuarios en tiempo real desde salesforce.

### Conceptos generales

1. ¿Qué significa SaaS?

    Software as a Service, es una manera de poner a disposición softwares y soluciones de tecnología en la nube, donde el proveedor no se tiene que preocupar por mantenimiento de la plataforma, pues proporciona actualizaciones automáticas y se muestra a los clientes en internet de forma automática a través de un pago.
2. ¿Salesforce es Saas?
    
    No ya que sales force es más bien una PaaS (Platform  as a Service), este concepto nació del resultado de SaaS.

3. ¿Qué significa que una solución sea Cloud?
    
    Significa que la solución se encuentra en la nube, por lo que es posible manejarlo de forma remota y permitir el acceso al software, almacenamiento de archivos y procesamiento de datos, por lo que no se necesita de una computadora personal en específico o servidor local.

4. ¿Qué significa que una solución sea On-Premise?
    
    Significa que la solución se encuentra en la empresa, ya que la integración del programa es realizado de forma local en la empresa y con ello obliga a crear una infraestructura compleja con los servidores que requieren mantenimiento.

5. ¿Qué es un pipeline de ventas?

    Es una herramienta que te ayuda a comprender los pasos de un proceso de ventas que se llevan a cabo de principio a final.

6. ¿Qué es un funnel de ventas?
    
    Es un sistema diseñado para atraer desconocidos hacia la empresa y convertirlos en clientes potenciales, para finalmente hacerlos clientes.

7. ¿Qué significa Customer Experience?
    
    Es la experiencia cliente, la impresión que da la marca al consumidor a lo largo de cada interacción con ella.

8. ¿Qué significa omnicanalidad?
    
    Son las estrategias que lleva a cabo una  empresa a través de todos los canales de comunicación, tanto online como físicos para mejorar la experiencia del cliente, permitiendo estar en contacto constante con la empresa.

9. ¿Qué significa que un negocio sea B2B?¿Qué significa que un negocio sea B2C?¿Qué es un KPI?
    
    El significado de B2B es Business to business, por lo que refiere a las ventas de una empresa a otra empresa, osea la compañía es proveedor y los clientes son empresas.
    
    En cuanto a B2C (Businees to costumer), esto quiere decir que la empresa le vende directo al consumidor.
    
    KPI o mejor conocido como Indicador Clave de Desempeño, lo cual hace referencia a una serie de métricas cuantitativas que se encuentran alineadas al objetivo de la empresa, por lo que sirven para medir el desempeño de proyectos, actividades y metas de un negocio.

10. ¿Qué es una API y en qué se diferencia de una Rest API? 

    API es un mecanismo que permite comunicarse entre dos componentes de software entre sí, mediante un conjunto de definiciones y protocolos. Lo que diferencia a una api rest es que no se encuentra vinculado a ninguna tecnología o plataforma en particular, ya que es independiente del idioma

11. ¿Qué es un Proceso Batch?
    
    Es el proceso mediante el cual una computadora completa lotes de trabajos, en varias ocasiones, de manera simultánea, de manera continua y secuencial.

12. ¿Qué es Kanban?
    
    Es un método visual de gestión de proyectos, que consiste en la gestión del flujo de trabajo para definir, gestionar y mejorar los servicios que proporcionan un trabajo de conocimiento, ayudando a visualizar el trabajo, maximizar la eficiencia y mejorar continuamente.
13. ¿Qué es un ERP? 

    También conocida como planificación de recursos empresariales, es un sistema que automatiza y administra los procesos empresariales de varias formas ya sea en finanzas, fabricación, ventas, cadena de suministros etc.

14. ¿Salesforce es un ERP?
    
    Salesforce es considerado un sistema CRM, sin embargo en actualidad también se está convirtiendo en un sistema ERP. Ya que gracias a las aplicaciones integradas a terceros logra abordar funcionalidades más allá de CRM.







  
