# Retos_Innovaccion 

# INTELIGENCIA ARTIFICIAL

- ## **Hardware**

Conjunto de elementos físicos o materiales que constituyen una computadora o un sistema informático.

![](https://www.google.com/url?sa=i&url=https%3A%2F%2Fsalesystems.es%2Fel-hardware-tipos-de-harware%2F&psig=AOvVaw1xgHtVL3Hel45HnVngaRyQ&ust=1620717174105000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCKD6-pHIvvACFQAAAAAdAAAAABAD)

- ## **Software**

Conjunto de programas y rutinas que permiten a la computadora realizar determinadas tareas.

![](https://lh3.googleusercontent.com/proxy/IOLq1LigW3LCLnR0Ci4Knbzg6wq3zRaBRE6WhYkTmtau1ykiscJhWWYJ---C_ZSXdjx2T47IP0IT3t2CnCHn3KIMEMcck9GjOeY5i7-8HPgxYF7f1gIoxmnL)

- ## **¿Cómo funciona el internet?**

Internet es la columna vertebral de la Web, la infraestructura técnica que la hace posible. En lo más básico, Internet es una gran red de computadoras que se comunican simultáneamente.

### **Una simple red**

Cuando dos ordenadores necesitan comunicarse, tienes que vincularlos, ya sea físicamente (por lo general con un cable de Ethernet) o de forma inalámbrica (por ejemplo por WiFi o sistema de Bluetooth). Todos los ordenadores modernos pueden soportar cualquiera de este tipo de conexiones.

![A a B](https://media.prod.mdn.mozit.cloud/attachments/2014/08/22/8441/ea681a48c79629e6a2a9540515fa70d7/internet-schema-1.png)

La red no se limita a dos ordenadores, se pueden conectar tantos como se deseen aunque siendo más complicado cada vez. Por ejemplo, para conectar diez ordenadores, se necesitarían 45 cables y unos nueve conectores por ordenador.

![Multiple red](https://media.prod.mdn.mozit.cloud/attachments/2014/08/22/8443/563aefd8abf5018a8768564687c5bdeb/internet-schema-2.png)

Para resolver este problema, cada ordenador en una red está conectado a una pequeña computadora especial llamada enrutador o router (en inglés). Este enrutador cumple una función: tal como hace un señalizador en una estación de tren, el router se encarga de asegurar que el mensaje enviado desde un ordenador emisor llegue al destino correcto. Para que el ordenador B reciba un mensaje desde el ordenador A, este debe enviarlo primero al router, quien a su vez lo remite al ordenador B asegurándose que dicho mensaje no sea entregado a otro ordenador C.  

Una vez que agregamos un enrutador al sistema, nuestra red de 10 ordenadores solo requiere 10 cables: un enchufe para cada ordenador y un enrutador con 10 enchufes.

![Conexión](https://media.prod.mdn.mozit.cloud/attachments/2014/08/22/8445/961f9b7a5cd49e58f23745680f328530/internet-schema-3.png)

### **Una red de redes**

Hasta aquí todo es más o menos simple, pero ¿qué sucede al conectar cientos, miles, millones de ordenadores entre sí?. Por supuesto un solo enrutador no puede escalar tanto, pero, si lees cuidadosamente, dijimos que un enrutador es como un pequeño ordenador, entonces ¿qué nos impide conectar dos enrutadores a la vez?. Nada: hagámoslo.

![Routers](https://media.prod.mdn.mozit.cloud/attachments/2014/08/22/8447/18611ed10de3e11e38f8a99246e536c6/internet-schema-4.png)

Conectando ordenadores a enrutadores y luego enrutadores entre sí, podemos escalar infinitamente.

![](https://media.prod.mdn.mozit.cloud/attachments/2014/08/22/8449/54e24828741ca7a790ccbbfb5600b586/internet-schema-5.png)

Una red así se acerca mucho a lo que llamamos Internet, pero hay algo que nos falta. Construimos esa red para nuestros propios propósitos. Hay otras redes ahí fuera: tus amigos, tus vecinos, cualquiera puede tener su propia red de ordenadores. Pero no es posible instalar cables entre tu casa y el resto del mundo, así que ¿cómo puedes manejar esto? Bueno, ya hay cables conectados a tu casa, por ejemplo, la energía eléctrica y el teléfono. La infraestructura telefónica ya conecta tu casa con cualquier persona en el mundo, así que es el cable perfecto que necesitamos. Para conectar nuestra red a la infraestructura telefónica, necesitamos un equipo especial llamado modem. Este modem convierte la información de nuestra red en información manejable por la infraestructura telefónica y viceversa.

![](https://media.prod.mdn.mozit.cloud/attachments/2014/08/22/8451/4a71df9d5b0961e113c099b78e476ea7/internet-schema-6.png)

Entonces estamos conectados a la infraestructura telefónica. El siguiente paso es enviar el mensaje desde nuestra red a la red que queremos llegar. Para lograr eso, conectaremos nuestra red a un proveedor de servicios de internet (ISP de sus siglas en inglés Internet Service Provider). Un ISP es una empresa que gestiona algunos enrutadores especiales interconectados, que también pueden acceder a enrutadores de otros ISP. Así, el mensaje de nuestra red es llevada a través de la red de redes de ISP, hasta la red de destino. Internet consiste en toda esta infraestructura de redes.

![](https://media.prod.mdn.mozit.cloud/attachments/2014/08/22/8453/62b5d675e5881278ab3aec994f4fb9f4/internet-schema-7.png)

### **Encontrando ordenadores**

Si deseas enviar un mensaje a una computadora, debes especificar a cuál. Es por ello que todo ordenador conectado a una red cuenta con una dirección única que lo identifica, llamada “dirección IP” o Protocolo de Internet(IP de sus siglas en inglés Internet Protocol). Esta dirección está compuesta por una serie de cuatro números separados por puntos, por ejemplo: 192.168.2.10.

Para los ordenadores es un identificador simple, pero los humanos tienen mayor dificultad a la hora de recordar y memorizar este tipo de dirección. Con el propósito de convertir esta serie numérica en algo que podamos asociar con mayor facilidad a la dirección IP se utiliza lo que conocemos como nombre de dominio. Por ejemplo, google.com es el nombre de dominio utilizado para sustituir la dirección IP 173.194.121.32. Así, usar un nombre de dominio es la manera más fácil para nosotros de identificar un ordenador a través de Internet.

![](https://media.prod.mdn.mozit.cloud/attachments/2014/08/21/8405/edb9541101a98f8fec92d5ec5d921670/dns-ip.png)

### **Internet y la web**

Como puedes notar, cuando navegamos por la web con un navegador, normalmente utilizamos el nombre de dominio para llegar a un sitio web. ¿Significa eso que Internet y la Web son la misma cosa? No es tan simple. Como vimos, Internet es una infraestructura técnica que permite que miles de millones de ordenadores estén conectadas entre sí. Algunos de estos ordenadores, llamados servidores web son capaces de enviar mensajes inteligibles a los navegadores. Por tanto Internet es una infraestructura, mientras que la Web es un servicio construido sobre dicha infraestructura. Cabe señalar que existen otros servicios soportados por Internet, como es el correo electrónico e IRC.

- ## **Frontend y Backend**

Descubre comunicación nos dice:

![](https://descubrecomunicacion.com/wp-content/uploads/2019/07/forndend-backend-post2.jpg)

Son dos partes fundamentales de la programación de una aplicación web. 

### **Frontend**

Es la parte de una aplicación que interactúa con los usuarios, es conocida como el lado del cliente. Básicamente es todo lo que vemos en la pantalla cuando accedemos a un sitio web o aplicación: tipos de letra, colores, adaptación para distintas pantallas(RWD), los efectos del ratón, teclado, movimientos, desplazamientos, efectos visuales… y otros elementos que permiten navegar dentro de una página web. Este conjunto crea la experiencia del usuario. Debe ser una interface sencilla de usar, atractiva y funcional.

Un desarrollador frontend debe conocer los siguientes lenguajes de programación: HTML5, CSS3, JavaScript, Jquery, Ajax.

![](https://descubrecomunicacion.com/wp-content/uploads/2019/07/frondend-programing-language.jpg)

### **Backend**

es todo con lo que el usuario se encuentra directamente en la web o aplicación, entonces cuando hablamos de “Back end” nos referimos al interior de las aplicaciones que viven en el servidor y al que a menudo se le denomina “el lado del servidor”.

El back end del sitio web consiste en un servidor, una aplicación y una base de datos. Se toman los datos, se procesa la información y se envía al usuario.  Los desarrolladores de Front end y Back end suelen trabajar juntos para que todo funcione correctamente.

Un desarrollador Back end debe tener amplios conocimientos de los siguientes lenguajes: frameworks y los tipos de base de datos. No siendo necesario conocer todos los lenguajes pero sí entender y saber trabajar con algunos de ellos.

ASP.NET , PHP, Python, Ruby, Node.js, Java, MySQL, SQL Server, PostgreSQL, Oracle, MongoDB.

![](https://descubrecomunicacion.com/wp-content/uploads/2019/07/backend-database.jpg)

### **Full Stack**

Por otro lado, un desarrollador Full Stack es el encargado de manejar cada uno de los aspectos relacionados con la creación y el mantenimiento de una aplicación web. Para ello es fundamental que el desarrollador Full Stack tenga conocimientos en desarrollo Front-End y Back-End además de manejar diferentes sistemas operativos y lenguajes de programación.

### **IasS (infraestructura como servicio)**

Es una oferta de computación en nube en la que un proveedor proporciona a los usuarios acceso a recursos informáticos, tales como: servidores, almacenamiento y redes. Las organizaciones utilizan sus propias plataformas y aplicaciones dentro de la infraestructura de un proveedor de servicios

### **PasS (Plafora como servicio)**

Es un entorno de desarrollo e implementación completo en la nube, con recursos que permiten entregar todo, desde aplicaciones sencillas basadas en la nube hasta aplicaciones empresariales sofisticadas habilitadas para la nube.

### **SasS (Software como servicio)**

Es una forma de disponibilizar softwares y soluciones de tecnología por medio de la internet, como un servicio. Con ese modelo, su empresa no necesita instalar, mantener y actualizar hardwares y softwares. El acceso es fácil y simples: solo es necesario conexión con la internet.


### **Iot**

El Internet de las cosas (IoT) es un nombre para la colección agregada de dispositivos habilitados para red, excluyendo los ordenadores tradicionales como computadoras portátiles y servidores. Los tipos de conexiones de red pueden incluir conexiones Wi-Fi, conexiones Bluetooth y comunicación de campo cercano (NFC). El IoT incluye dispositivos como electrodomésticos "inteligentes", como refrigeradores y termostatos; sistemas de seguridad para el hogar; periféricos informáticos, como cámaras web e impresoras; tecnología wearable,como Apple Watches y Fitbits; routers; y dispositivos de altavoces inteligentes, como Amazon Echo y Google Home.

![](https://www.how2shout.com/wp-content/uploads/2018/10/What-is-internet-of-things-IOT.png)

### **BIG DATA**
Big data es un término que describe el gran volumen de datos – estructurados y no estructurados – que inundan una empresa todos los días. Pero no es la cantidad de datos lo importante. Lo que importa es lo que las organizaciones hacen con los datos. El big data puede ser analizado para obtener insights que conlleven a mejores decisiones y acciones de negocios estratégicas.

![image](https://user-images.githubusercontent.com/83653403/117557390-01d00800-b038-11eb-9b48-a6558d59a3af.png)

***Volumen*** 
Las organizaciones recopilan datos de diversas fuentes, como transacciones comerciales, dispositivos inteligentes (IO), equipo industrial, vídeos, medios sociales y más. En el pasado, su almacenamiento habría sido un problema - pero el almacenamiento más barato en plataformas como los data lakes y el Hadoop han aliviado la carga.

![image](https://user-images.githubusercontent.com/83653403/117557421-48bdfd80-b038-11eb-8eff-311c3c4ddf3d.png)

***Velocidad*** 
Con el crecimiento del Internet de las Cosas, los datos llegan a las empresas a una velocidad sin precedentes y deben ser manejados de manera oportuna. Las etiquetas RFID, los sensores y los medidores inteligentes están impulsando la necesidad de manejar estos torrentes de datos en tiempo casi real.

![image](https://user-images.githubusercontent.com/83653403/117557450-989cc480-b038-11eb-8015-f4c103b49799.png)

***Variedad***
Los datos se presentan en todo tipo de formatos: desde datos numéricos estructurados en bases de datos tradicionales hasta documentos de texto no estructurados, correos electrónicos, vídeos, audios, datos de teletipo y transacciones financieras.

***Variabilidad***
Además de las crecientes velocidades y variedades de datos, los flujos de datos son impredecibles, cambian a menudo y varían mucho. Es un reto, pero las empresas necesitan saber cuándo algo está de moda en los medios sociales, y cómo gestionar los picos de carga de datos diarios, estacionales y desencadenados por eventos.

***Veracidad***
La veracidad se refiere a la calidad de los datos. Debido a que los datos provienen de tantas fuentes diferentes, es difícil vincular, comparar, limpiar y transformar los datos a través de los sistemas. Las empresas necesitan conectar y correlacionar las relaciones, las jerarquías y los múltiples vínculos de datos. De lo contrario, sus datos pueden salirse de control rápidamente.

![](![image](https://user-images.githubusercontent.com/83653403/117557381-ec5ade00-b037-11eb-9ad8-03b84646aec5.png))

## <p>Computo <br>
Un equipo de computo es un dispositivo electrónico que cuenta con una tarjeta madre que es la que controla los demás componentes del equipo, un procesador, una memoria RAM (almacenamiento temporal de la información), Memoria de almacenamiento (donde se guarda la infomación del usuario y del sistema) y software que es la conección entre el usuario y el equipo, gracias al cual el usuario puede asignar órdenes al equipo para realizar procesos. </p>
Esta es la estructura base de un equipo de computo, dependiendo del tipo de equipo puede estar acompañando en un teclado, ratón y monitor o solamente una pantalla táctil que suple las funciones del teclado y ratón como es el caso de los celulares y tabletas. </p>
![partes de la computadora](http://www.accesoriosparacomputadores.co/blog/wp-content/uploads/2015/03/principales-partes-del-computador.jpg)
## Comunicación entre equipos de computo <br>
Los equipos de computo pueden comunicarse o transmitir información principalmente a través de señales infrarojas (en el pasado), por señales de radio bluethood y redes (eternet y wifi). Además para que los equipos de computo se puedan comunicar requierende un lenguaje o protocolo de comunicación </p>
La comunicación por medio de redes es la que permite la transferencia de datos con la mayor velocidad y es la más utilizada en la comunicación entre computadoras. </p>
El lenguaje de comunicación se conoce como TCP/IP (Protocolo de Control de Transmisión/Protocolo de Internet). Mediante este leguaje se pueden transferir datos entre equipos de computo dentro de una misma infraestructura 8red local) o servidor y por medio de internet entre diferentes infraestructuras o servidores los cuales pueden estar ubicados incluso continentes diferentes, además esta comunicación permite que de manera remota se pueda operar un equipo de computo desde otra ubicación física </p>
El modelo OSI explica las redes de comunicación en 7 capas o niveles: </p>
- **Nivel físico**: Señal y transmisión binaria </p>
- **Nivel de enlace de datos**: direccionamiento físico </p>
- **Nivel red**: Determinación de ruta e IP (direccionamiento lógico) </p>
- **Nivel de transporte**: conexión extremo- extremo y fiabilidad de los datos </p>
- **Nivel sesión**: comunicación entre dispositivos de la red </p>
- **Nivel de Presentación**: Representación de los datos </p>
- **Nivel aplicación**: servicios de red a aplicaciones </p>
![Comunicacion entre equipos de cómputo](http://www.alegsa.com.ar/Diccionario/Imagenes/modelo_osi.png)
## <p> Nube <br>
Conocido como el computo en la nube, es un sevicio que permite la disponibilidad y uso de recursos de almacenamiento y capacidad de computo, como memoria RAM y procecadores, de forma remota desde otro dispositivo de computo mediante el uso de redes. </p>
Los recursos y servicios que ofrecen las nubes son impresionantes y le permiten al usuario disponer de datos sin tener que almacenarlos físicamente en su dispositivo, además permite de manera sencilla y rápida el compartir esta información, también funciona como un respaldo de esta información. </p>
Pero el almacenamiento no es lo único, también se puede usar de forma remota que equipos de computo con mayor capacidad de procesamiento y memoria sin tener que comprar una computadora muy potente, puesto que se puede rentar por un determinado tiempo reduciendo de esta forma los gastos de capital, otro de los servición de la nube es el uso de aplicaciones especializadas.
<br>
![nube](https://www.muycomputer.com/wp-content/uploads/2015/02/Almacenamiento_Nube-630x450.jpg)
<br>
## Tipos de nubes
#### Existen tres tipos de nube:
- **Nube privada**:
Una persona, organización o empresa es dueña de la infraestructura, es decir, de los servidores, el espacio físico donde estos se encuentran, se encarga del software y su configuración. El uso de este recurso es restringido y el mantenimiento es responsabilidad del dueño de la nube

- **Nube pública**:
Se denomina así cuando los recursos y servicios de la nube están a disposición de cualquier usuario que desee contratar dicho servicio. Bajo este esquema el mantenimiento de la nube corre bajo la responsabilidad del dueño de la nube y el usuario no tiene de que preocuparse por eso.
- **Nube híbrida**:
En este esquema el usuario (organización o empresa) es dueño de su nube pero además contrata los servicios de una nube pública para y correr algunas aplicaciones en estos servidores, de esta forma el usuario pude incrementar su capacidad de operación cuando lo requiera.
![Tipos de nubes](https://www.muycomputerpro.com/wp-content/uploads/2018/07/nube-hibrida.jpg)
## Servicios que ofrecen las nubes
- **IAAS (Infraestructura como servicio)**: La nube provee el servidor, maquina virtual con la memoria y procesamiento deseado pero el software y configuración corren por cuenta del usuario
- **PAAS (Plataforma como servicio)**: La nube provee el servidor, memoria, procesamiento y sistema operativo pero el usuario debe instalar sus aplicaciones así como encargarse de toda la configuración de estas
- **SAAS (Software como servicio)**: La nube provee tanto la infraestructura como el software que neesita el usuario para correr sus procesos

La nube provee tanto la infraestructura como el software que neesita el usuario para correr sus procesos

![Servicios que ofrecen las nubes](https://profile.es/wp-content/media/modelos-servicios-cloud-iaas-paas-saas.jpg)

## Servicios Azure
Azure es la nube de Microsoft que permite el uso de recursos y aplicaciones al rededor del mundo. Azure provee más de 100 servicios que permiten hacer cualquier cosa desde correr una aplicación existente hasta explorar nuevos paradigmas en software como inteligancia artificial y realidad aumentada. Los servicios más utilizados de Azure se pueden resumir de la siguiente forma:
<ul>
<li><h3>Servicios de infraestructura</h3>
<ul>
<li><b>Computo</b>: Maquinas vituales y Contenedores</li>
<li><b>Almacenamiento</b>: BLOB Storage, Azzure files, Premium Storage</li>
<li><b>Redes</b>: Virtual Network, Load Balancer, DNS, Express Router, Traffic Manager, VPN Gateway y Application Gateway</li>
</ul>
</li>
<li><h3>Servicios de plataforma</h3>
<ul>
<li><b>Computo</b>: Cloud Services, Services Fabric, Batch y Remote App</li>
<li><b>Web and mobile</b>: Web Apps, API Apps, API Managment, Mobile Apps, Logic Apps y Notification Hubs</li>
<li><b>Servicios de desarrollador</b>: Visual Studio, Azure SDK, Team Project y Applications Insights</li>
<li><b>Integración</b>: Storage Queues, BizTalk Services, Hybrid Connections y Service Bus</li>
<li><b>Analytics and IOT</b>: HDInsight, Machine Learning, Data Factory, Event Hubs, Stream Analytics y Mobile Engagement</li>
<li><b>Datos</b>: SQL Database, SQL Data Warehouse, Redis Cache, Search, cosmos DB y Tables</li>
<li><b>Media and CDN</b>: Media Services y Content Delivery Network (CDN)</li>
</ul>
</li>
<li><b>Operaciones Híbridas</b>: Azure AD Connect Health, Ad Privileged Identity Management, Backup, Operational Insights, Import/Export, Site Recovery y StorSimple</li>
<li><b>Servicios de Seguridad</b>: Portal, Active Directory, multi-Factor Authentication, Automation, Key Vault, Store/Marketplace y VM Image Gallery and VM Depot</li>
</ul>
<img src="https://www.keykumo.com/wp-content/uploads/2016/08/azure-keykumo.png"></img>
<h2>Zonas de Azure</h2>
<b>Regiones</b>: Son áreas geográficas del planeta que tienen al menos uno centro de datos, pero potencialmente más, que son cercanos entre sí con una red de baja latencia.
<br>
<b>Geograficas</b>: Son regiones geopolíticas o fronteras entre paíces que tienen 2 o más regiones que preservan el almacenamiento de los datos. La geografía esta dividida en las siguientes áreas:
<ul>
<li><b>Americanas</b></li>
<li><b>Europa</b></li>
<li><b>Asia-Pacífico</b></li>
<li><b>Oriente medio y África</b></li>
<li><b>Zonas de disponibilidad</b>: Se llama así a las zonas conformada por centros de datos que interactuan entre sí guardando la información como duplicado una de otras, es decir la inforación de un centro de datos también esta almacenada en el otro centro de datos. Una condición importante es que los centros de datos deben estar lo suficiente separados uno de otro para no ser afectados por los mismos fenómenos naturales.</li></ul>
<img src="https://azurecomcdn.azureedge.net/cvt-93da322b8e36592b6fa17faa77857ee4467225501ecd84a7c5466e5d0f790b30/images/shared/regions-map-mobile.svg"/>
<h2> Creación de la cuenta de Azure</h2>
Con la creación de una cuenta Azure se pueden crear, probar e implementar aplicaciones empresariales. Además de crear aplicaciones web y experiencia mobiles, así como obtenger información de sus datos a través del aprendizaje automático y analítico.
En odas las cuentas se debe especificar el nombre, email, información de contacto, información de facturación y tarjeta de crédito, existen varios tipos de cuentas: 
<ul>
<li> Subscripción gratuita: Esta suscripción incluye un crédito de 200 usd para ser utilizados en cualquier servicio durante un lapso de 30 días. libre acceso a los productos más populares de Azure durante 12 meses. Para crearla se necesita un número telefónico, una tarjeta de crédito y una cuenta de Microsoft. - Subscripción Pay-as-you-go: En esta subscripción se cobra mensualmente por los servicios utilizados durante el periodo. esta es la más apropiada para la mayoría de los usuarios desde individuos hasta pequeñas empresas y algunas organizaciones grandes.</li>
<li> Subcripción Pay-as-you-go DEV/TEST Esta esta diseñada para subcriptores de Visual Studio y se limita exclusivamente para desarrollo y pruebas
- Azure Enterprise Agreement esta provee la mayor flexibilidaden la compra de servicios en la nube, ademas de contar con descuentos de nuevas licencias de seguros de Softwares.
<li> Subcripción Azure para estudiantes Esta incluye un crédito de 100 usd para ser usado en los primeros 12 meses además de poder seleccionar servicios sin requerimeinto de tarjeta de crédito. Solo se tiene que demostrar que se es estudiante.</li>
<li> Múltiples subcripciones con una misma cuenta: Es muy utilizado por empresas para controlar el acceso y facturación.</li>
</ul>


