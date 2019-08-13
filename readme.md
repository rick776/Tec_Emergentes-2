# Práctica N° 1 #
## Sistemas empresariales ##

**1. Explique que son los sistemas empresariales**

Un sistema empresarial es un sistema central de la organización, que garantiza que la información se pueda transmitir a través de todas las funciones empresariales, y todos los niveles de gestión, para soportar la operación y administración de una empresa. Panorama de los sistemas empresariales: sistema de proceso de transacciones y planeación de recursos empresariales. Todas las organizaciones de procesamiento de transacción de datos (TPC), que capturan y procesan información con el detalle necesario para actualizar registros acerca de sus operaciones empresariales, la entrada de estos sistemas son las transacciones empresariales como: pedidos, órdenes de compras, recibos y facturas entre otros. 

**2. Describa cuales son las características más importantes de una aplicación empresarial**

- Integración con las redes sociales
- Funcionalidad de búsqueda
- Permitir comentarios del usuario
- Diseño adaptado a diferentes dispositivos y tamaños de pantalla
- La capacidad de trabajar fuera de línea

**3. Investigue y proponga cinco (5) instituciones que requerirían aplicaciones de misión crítica. Justifique su respuesta**



**4. Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical**


- Escalabilidad vertical

La escalabilidad vertical o hacia arriba, este es el más simple, pues significa crecer el hardware de uno de los nodos, es decir aumentar el hardware por uno más potente, como disco duro, memoria, procesador, etc. pero también puede ser la migración completa del hardware por uno más potente. El esfuerzo de este crecimiento es mínimo, pues no tiene repercusiones en el software, ya que solo será respaldar y migrar los sistemas al nuevo hardware.
la realidad es que este tipo de escalamiento tiene algunos aspectos negativos, ya que nuestro crecimiento está ligado al hardware, y este; tarde o temprano tendrá un límite, llegara el momento que tengamos el mejor procesador, el mejor disco duro, la mejor memoria y no podamos crecer más o podríamos a lo mejor comprar el siguiente modelo de servidores que nos costara un ojo de la cara y el rendimiento solo mejorar un poco, lo que nos traerá el mismo problema el próximo año.
Ahora bien, no significa que este modelo de escalamiento sea malo, ya que lo podemos combinar con el escalamiento horizontal para obtener mejores resultados.


- Escalabilidad horizontal

El escalamiento horizontal es sin duda el más potente, pero también el más complicado. Este modelo implica tener varios servidores (conocidos como Nodos) trabajando como un todo. Se crea una red de servidores conocida como Cluster, con la finalidad de repartirse el trabajo entre todos nodos del cluster, cuando el performance del cluster se ve afectada con el incremento de usuarios, se añaden nuevos nodos al cluster, de esta forma a medida que es requeridos, más y más nodos son agregados al cluster.
Para que el escalamiento horizontal funcione deberá existir un servidor primario desde el cual se administra el cluster. Cada servidor del cluster deberá tener un software que permite integrase al cluster, por ejemplo, para las aplicaciones Java, tenemos los servidores de aplicaciones como Weblogic, Widfly, Websphere, etc. y sobre estos se montan las aplicaciones que queremos escalar.

**5. Que es un servidor Web y que es un servidor de aplicaciones**


- Servidor web

Un servidor web o servidor HTTP es un programa informático que procesa una aplicación del lado del servidor realizando conexiones bidireccionales y/o unidireccionales y síncronas o asíncronas con el cliente generando o cediendo una respuesta en cualquier lenguaje o Aplicación del lado del cliente. El código recibido por el cliente suele ser compilado y ejecutado por un navegador web. Para la transmisión de todos estos datos suele utilizarse algún protocolo. Generalmente se utiliza el protocolo HTTP para estas comunicaciones, perteneciente a la capa de aplicación del modelo OSI. El término también se emplea para referirse al ordenador que ejecuta el programa. 


- Servidor de aplicaciones

En informática, se denomina servidor de aplicaciones a un servidor en una red de computadores que ejecuta ciertas aplicaciones.
Usualmente se trata de un dispositivo de software que proporciona servicios de aplicación a las computadoras cliente. Un servidor de aplicaciones generalmente gestiona la mayor parte (o la totalidad) de las funciones de lógica de negocio y de acceso a los datos de la aplicación. Los principales beneficios de la aplicación de la tecnología de servidores de aplicación son la centralización y la disminución de la complejidad en el desarrollo de aplicaciones.

**6. Con un gráfico explique cómo funciona el protocolo HTTP**

![http](https://www.miguelra.com/content/images/2016/12/comunicacionHTTP-1.jpg)

**7. Explique los elementos importantes de REQUEST en HTTP**

El comando HTTP Request permite enviar todo tipo de petición HTTP a un URL específico y procesar la respuesta del servidor HTTP.
El objeto Request
En inglés, request significa pedir, solicitar. En efecto, la acción de escribir una dirección cualquiera en la línea de URL de tu navegador, se traduce en solicitar un determinado fichero a un servidor, o dicho en la jerga técnica, se le hace un request al servidor. El protocolo que utiliza el navegador (por defecto salvo que se indique otro, como el FTP) para dialogar con un servidor web es el llamado HTTP, que como habrás visto figura al principio de todas las direcciones web. No es necesario escribir el protocolo en los navegadores modernos, simplemente escribimos la dirección de la página solicitada, y el navegador añade delante de la misma su protocolo por defecto. Por ejemplo, si escribes:
   sestud.uv.es/manual.esp/ el navegador compone http://sestud.uv.es/manual.esp/
El objeto Request permite el acceso a toda la información que pasa desde el navegador del cliente al servidor. Al recibir esta información, es repartida y almacenada entre cinco colecciones. Cada colección es similar en estructura a una tabla de datos (también llamada matriz de datos o array). Los datos, una vez cargados, pueden ser accedidos individualmente en cada colección a través de una única clave asignada a cada item.
Todas las variables pueden ser accedidas directamente mediante una llamada del tipo Request(variable) sin mencionar el nombre de la colección. En este caso, el servidor web busca entre todas las colecciones la clave pedida (variable).


**8. Explique los elementos importantes de RESPONSE en HTTP**

**9. Describa con un gráfico la arquitectura Java EE**

![javaEE](http://abhirockzz.files.wordpress.com/2014/01/overview-multitieredapplications.gif)

**10. Explique cuáles son los contenedores, componentes y servicios de Java EE**

**11. Investigue los métodos más utilizados de las clases HttpServlet, HttpServletRequest y HttpServletResponse, y para cada uno de los métodos muestre un ejemplo.**