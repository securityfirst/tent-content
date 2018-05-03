[Title]: # ()
[Order]: # (0)

# GUÍA DE HERRAMIENTAS PIDGIN

## Guía de la herramienta Pidgin
Mensajería instantánea cifrada para Windows

**Lección para leer:** [Enviar un mensaje](umbrella://lesson/sending-a-message)
**Ubicación de descargas:**
- [https://pidgin.im/download/](https://pidgin.im/download/)
- [https://otr.cypherpunks.ca/](https://otr.cypherpunks.ca/)

**Requisitos de la computadora:** Una conexión a Internet, una computadora con Windows XP o superior y una cuenta XMPP (Jabber). _(Pidgin puede trabajar con muchos sistemas de chat, como AIM, Facebook, Google Talk, MSN, MXit y Yahoo, pero aquí nos centraremos en XMPP, anteriormente conocido como Jabber)_  
**Versión utilizada en esta guía:**
- Windows 7 Ultimate
-Pidgin 2.10.9, pidgin-otr 4.0.0-1

**Licencia:** Software libre; combinación de licencias de Software Libre  
**Nivel:** Principiante  
**Otra lectura:** [https://pidgin.im/cgi-bin/mailman/listinfo/support](https://pidgin.im/cgi-bin/mailman/listinfo/support)  
**Tiempo requerido:** 20 minutos  

**El uso de OTR con Pidgin le dará:**
- La capacidad de organizar y administrar algunas de las servicios de mensajería instantánea más populares a través de un solo programa.
- La capacidad de tener chats cifrados en mensajería instantánea, sin que el servidor inicie sesión en esos chats.
- La capacidad de asegurarse de que la persona con la que está chateando realmente es esa persona.

### 1.0 Antes de comenzar

Pidgin es un cliente de mensajería instantánea fácil de usar para Windows que usa un protocolo llamado OTR (Off-the-record), que permite a los usuarios mantener conversaciones confidenciales.

- **Nota:** OTR no debe confundirse con "Off the record" de Google, que solo deshabilita el registro de chat, y no tiene capacidades de cifrado o verificación.
-Pidgin admite los siguientes servicios de mensajería instantánea: AIM, Bonjour, Gadu-Gadu, Google Talk, Groupwise, ICQ, IRC, MSN, MXit, MySpaceIM, SILC, SIMPLE, Sametime, Yahoo !, Zephyr y cualquier cliente de mensajería instantánea que ejecute XMPP protocolo de mensajes.
- Pidgin no permite la comunicación entre diferentes servicios de mensajería instantánea. Por ejemplo, si está usando Pidgin para acceder a su cuenta de Google Talk, no podrá chatear con un amigo usando una cuenta ICQ.
- Sin embargo, Pidgin puede configurarse para administrar varias cuentas según cualquiera de los protocolos de mensajería compatibles. Es decir, puede usar simultáneamente cuentas de Gmail e ICQ, y chatear con corresponsales usando cualquiera de esos servicios específicos (que son compatibles con Pidgin).
- Pidgin, automáticamente registra las conversaciones por defecto, sin embargo, usted tiene la capacidad de desactivar esta función. Dicho esto, no tienes control sobre la persona con la que estás chateando: podría iniciar sesión o tomar capturas de pantalla de tu conversación, incluso si tú mismo has desactivado el registro.

**¿Por qué debería usar Pidgin + OTR?**
Cuando tienes una conversación de chat usando Google Hangouts o chat de Facebook en los sitios web de Google o Facebook, ese chat se encripta usando HTTPS, lo que significa que el contenido de tu chat está protegido de piratas informáticos y otros terceros mientras está en tránsito. Sin embargo, no está protegido de Google o Facebook, que tienen las claves de sus conversaciones y puede entregarlas a las autoridades.

Después de haber instalado Pidgin, puede iniciar sesión usando varias cuentas al mismo tiempo. Por ejemplo, puede usar Google Hangouts, Facebook y XMPP simultáneamente. Pidgin también te permite chatear usando estas herramientas sin OTR. Dado que OTR solo funciona si las dos personas lo están usando, esto significa que incluso si la otra persona no lo tiene instalado, puedes seguir chateando con Pidgin.

Pidgin también te permite hacer una verificación fuera de banda. asegúrese de estar hablando con la persona con la que cree que está hablando. Para cada conversación, hay una opción que le mostrará las huellas dactilares clave que tiene para usted y la persona con la que está chateando. Una "huella dactilar de clave" es una cadena de caracteres como "342e 2309 bd20 0912 ff10 6c63 2192 1928," que se usa para verificar una clave pública más larga. Intercambie sus huellas dactilares a través de otro canal de comunicación, como Twitter DM o correo electrónico, para asegurarse de que nadie interfiera con su conversación.

**Limitaciones: ¿cuándo no debería usar Pidgin + OTR?**

Pidgin es un programa complejo, que no se ha escrito con la seguridad como una prioridad principal. Es casi seguro que tiene errores, algunos de los cuales podrían ser utilizados por los gobiernos o incluso las grandes empresas para entrar en las computadoras que lo están usando. Usar Pidgin para encriptar tus conversaciones es una gran defensa contra el tipo de vigilancia no focalizada que se utiliza para espiar las conversaciones de Internet de todos, pero si crees que serás atacado personalmente por un atacante con recursos suficientes (como un estado-nación), debería considerar precauciones más estrictas, como el correo electrónico PGP encriptado.

### 2 Descarga e instalación

### 2.1 Obtención de Pidgin

Puede obtener Pidgin en Windows descargando el instalador de la descarga de Pidgin página.
![image](tool_pidgin1.png)

Haga clic en la pestaña _purple_ DOWNLOAD. _**No** haga clic en el botón verde Descargar ahora porque querrá elegir un archivo de instalación diferente._
Se lo dirigirá a la página de descarga.
![image](tool_pidgin2.png)

_De nuevo, **no** haga clic en el botón verde Descargar ahora porque queremos elegir un archivo de instalación diferente._  
El instalador predeterminado para Pidgin es pequeño porque no contiene toda la información y descarga los archivos para tú. A veces, esto falla, por lo que tendrá una mejor experiencia con el "instalador sin conexión" que contiene todo el material de instalación necesario.

Haga clic en el enlace "**instalador sin conexión**". Se lo dirigirá a una nueva página titulada "Sourceforge" y después de unos segundos, una pequeña ventana emergente le preguntará si desea guardar un archivo.

**Nota:** Si bien la página de descarga de Pidgin usa "HTTPS" y, por lo tanto, está relativamente a salvo de la manipulación, el sitio web que le indica que descargue la versión de Windows de Pidgin es actualmente Sourceforge, que utiliza "HTTP," sin cifrar y, por lo tanto, no ofrece protección. Eso significa que el software que descarga puede ser alterado antes de descargarlo. Este riesgo provendría principalmente de alguien con acceso a la infraestructura de Internet local que intenta realizar una vigilancia específica contra usted personalmente (por ejemplo, un proveedor de puntos de acceso malicioso), o un estado o gobierno que planea distribuir software comprometido a muchos usuarios. La extensión [HTTPS en todas partes](https://www.eff.org/https-everywhere) puede reescribir las URL de descarga de Sourceforge en HTTPS, por lo que se recomienda que instale HTTPS en todas partes antes de descargar cualquier otro software. Además, en nuestra experiencia, Sourceforge a menudo tiene anuncios confusos de página completa en sus páginas de descarga que pueden engañar a las personas para que instalen algo que quizás no quieran. Puede instalar un bloqueador de anuncios antes que cualquier otro software para evitar estos anuncios confusos.

Muchos navegadores le solicitarán que confirme si desea descargar este archivo. Internet Explorer 11 muestra una barra en la parte inferior de la ventana del navegador con un borde naranja.
![image](tool_pidgin3.png)

Para cualquier navegador, es mejor guardar primero el archivo antes de continuar, así que haga clic en "Guardar" botón. De forma predeterminada, la mayoría de los navegadores guardan los archivos descargados en la carpeta de descargas.

### 2.2 Obtención de OTR

Puede obtener pidgin-otr, el complemento OTR para Pidgin, descargando el instalador de la [página de descarga OTR](https://otr.cypherpunks.ca/).
![image](tool_pidgin4.png)
Haga clic en la pestaña "Descargas" para ir a la sección "Descargas" de la página. Haga clic en el enlace "Win32 installer for pidgin".
![image](tool_pidgin5.png)

Muchos navegadores le pedirán que confirme si desea descargar este archivo. Internet Explorer 11 muestra una barra en la parte inferior de la ventana del navegador con un borde naranja.
![image](tool_pidgin6.png)

Para cualquier navegador, es mejor guardar primero el archivo antes de continuar, haga clic en "Guardar" botón. De forma predeterminada, la mayoría de los navegadores guardan los archivos descargados en la carpeta de descargas.

Después de descargar Pidgin y pidgin-otr, debe tener dos archivos nuevos en su carpeta

Downloads:
![image](tool_pidgin7.png)

### 2.3 Instalación de Pidgin

Mantenga abierta la ventana del Explorador de Windows y haga doble clic en pidgin-2.10.9-offline.exe. Se le preguntará si desea permitir la instalación de este programa. Haga clic en el botón "Sí".
![image](tool_pidgin8.png)

Se abre una ventana pequeña que le solicita que seleccione un idioma. Haga clic en el botón "Aceptar".
![image](tool_pidgin9.png)

Se abrirá una ventana que le brindará una descripción general rápida del proceso de instalación. Haga clic en el botón "Siguiente".
![image](tool_pidgin10.png)

Ahora obtiene una descripción general de la licencia. Haga clic en el botón "Siguiente".
![image](tool_pidgin11.png)

Ahora puede ver qué componentes están instalados. No cambie la configuración. Haga clic en el botón "Siguiente".
![image](tool_pidgin12.png)

Ahora puede ver dónde se instalará Pidgin. No cambie esta información. Haga clic en el botón "Siguiente".
![image](tool_pidgin13.png)

Ahora verá una ventana con texto desplazable hasta que aparezca "Instalación completa." Haga clic en "Siguiente" button.
![image](tool_pidgin14.png)

Por último, verá la última ventana del instalador de Pidgin. Haga clic en el botón "Finish".
![image](tool_pidgin15.png)

### 2.4 Instalación de pidgin-otr

Vuelva a la ventana del Explorador de Windows y ábrala y haga doble clic en pidgin -otr-4.0.0-1.exe. Se le preguntará si desea permitir la instalación de este programa. Haga clic en el botón "Sí".
![image](tool_pidgin16.png)

Se abrirá una ventana que le brindará una descripción general rápida del proceso de instalación. Haga clic en el botón "Siguiente".
![image](tool_pidgin17.png)

Ahora obtiene una descripción general de la licencia. Haga clic en el botón "Acepto".
![image](tool_pidgin18.png)

Verá dónde se instalará pidgin-otr. No cambie esta información. Haga clic en el botón "Instalar".
![image](tool_pidgin19.png)

Por último, verá la última ventana del instalador pidgin-otr. Haga clic en el botón "Finish".
![image](tool_pidgin20.png)

### 3 Configuración

### 3.1 Configuración de Pidgin

Vaya al menú Inicio, haga clic en Icono de Windows, y seleccione Pidgin en el menú.
![image](tool_pidgin21.png)

### 3.2 Agregar una cuenta

Cuando Pidgin se lance por primera vez, verá que esta ventana de bienvenida está dando tienes la opción de agregar una cuenta. Como aún no tiene una cuenta configurada, haga clic en el botón "Agregar".
![image](tool_pidgin22.png)

Ahora verá la ventana "Agregar cuenta".

**_Pidgin puede trabajar con muchos sistemas de chat, como AIM, Facebook, GoogleTalk, MSN, MXit y Yahoo, pero aquí nos centraremos en XMPP, antes conocido como Jabber._**

* En la entrada Protocolo, seleccione la opción "XMPP".

* En la entrada Nombre de usuario, ingrese su nombre de usuario XMPP.

* En la entrada Dominio, ingrese el dominio de su cuenta XMPP.

* En la entrada Contraseña , ingrese su contraseña de XMPP.

Comprobar el cuadro con la entrada "Recordar contraseña" facilitará el acceso a su cuenta. Tenga en cuenta que al hacer clic en "Recordar contraseña," se guardará su contraseña en la computadora, haciéndola accesible a cualquier persona que pueda tener acceso a su computadora. Si esto es una preocupación, no marque esta casilla. A continuación, se le pedirá que ingrese la contraseña de su cuenta XMPP cada vez que inicie Pidgin.
![image](tool_pidgin23.png)

### 3.3 Agregar un amigo

Ahora querrá agregar a alguien a chatear con. Haga clic en el menú "Amigos" y seleccione "Agregar amigo". Se abrirá una ventana "Añadir amigo".
![image](tool_pidgin24.png)

En "Agregar ventana "puede ingresar el nombre de usuario de la persona con la que desea chatear. Este otro usuario no tiene que ser del mismo servidor, pero tiene que usar el mismo protocolo, como XMPP.

En la entrada "Buddy's username", ingrese el nombre de usuario de su amigo con el nombre de dominio. Esto se verá como una dirección de correo electrónico.

En la entrada "(Opcional) Alias", puede ingresar un nombre de su elección para su amigo. Esto es completamente opcional, pero puede ayudar si la cuenta XMPP de la persona con la que está chateando es difícil de recordar.

Haga clic en el botón "Agregar".
![image](tool_pidgin25.png)

Una vez que haya hecho clic en el botón "Agregar ", Boris recibirá un mensaje preguntándole si le da autorización para que lo agregue. Una vez que Boris lo haga, él agregará su cuenta y obtendrá la misma solicitud.

Haga clic en el botón "Autorizar".
![image](tool_pidgin26.png)

### 3.4 Configurando el plugin OTR

Ahora configurará el plugin OTR para que pueda chatear de manera segura . Haga clic en el menú "Herramientas" y seleccione la opción "Complementos".
![image](tool_pidgin27.png)

Desplácese hasta la opción "Off-the-Record Messaging" y compruebe la caja.

Haga clic en la entrada "Off-the-Record Messaging" y haga clic en el botón "Configurar Plugin".
![image](tool_pidgin28.png)

Ahora verá "Off -la ventana de configuración Registrar Mensajería". Observe que dice "No hay ninguna clave presente."

Haga clic en el botón "Generar".
![imagen](tool_pidgin29.png)

Ahora se abrirá una pequeña ventana y generará una clave. Cuando termine, haga clic en el botón "OK".
![image](tool_pidgin30.png)

Verá nueva información: una cadena de 40 caracteres de texto, dividida en 5 grupos de ocho caracteres . Esta es su huella dactilar OTR. Haga clic en el botón "Cerrar".
![image](tool_pidgin31.png)

Ahora haga clic en el botón "Cerrar" en la ventana de complementos.

### 4.0 Conversación segura

Ahora puedes chatear con Boris. Los dos pueden enviar mensajes de ida y vuelta. Sin embargo, todavía no estamos chateando de forma segura. Incluso si se está conectando al servidor XMPP, es posible que la conexión entre usted y Boris no sea segura desde el espionaje.

Si mira la ventana de chat, observe que dice "No privada" en rojo en la parte inferior derecha. Haga clic en el botón "No privado".
![image](tool_pidgin32.png)

Se abrirá un menú, seleccione "Authenticate buddy. "
![image](tool_pidgin33.png)

Se abrirá una ventana. Se le preguntará: "¿Cómo le gustaría autenticar a su amigo?"

El menú desplegable tiene tres opciones:

**Opción 1: secreto compartido**

Un secreto compartido es una línea del texto que usted y la persona que desea conversar han acordado usar con anticipación. Debes haber compartido esto en persona y nunca lo has intercambiado a través de canales inseguros como el correo electrónico o Skype.

Tú y tu amigo deben ingresar este texto juntos. Haga clic en el botón "Autenticar".
![image](tool_pidgin34.png)

La verificación secreta compartida es útil si usted y su amigo ya han hecho arreglos para conversar en el futuro pero aún no han creado OTR huellas dactilares en la computadora que está utilizando.

**Opción 2: verificación manual de huellas dactilares**

La verificación manual de huellas digitales es útil si ya recibió la huella dactilar de su amigo y ahora se está conectando con Pidgin. Esto no será útil si su amigo cambió de computadora o tuvo que crear nuevas huellas dactilares.

Si la huella digital que recibió y la huella digital en la pantalla coinciden, seleccione "Tengo" y haga clic en el botón "Autenticar" .
![image](tool_pidgin35.png)

**Opción 3: Pregunta y respuesta**

La verificación de preguntas y respuestas es útil si conoce a su amigo pero no ha establecido un secreto compartido ni tuvo una oportunidad de compartir huellas dactilares. Este método es útil para establecer la verificación basada en algo que ambos conocen, como un evento compartido o memoria.

Ingrese la pregunta que desea formular. No lo hagas tan simple que alguien pueda adivinarlo fácilmente, pero no lo hagas imposible. Un ejemplo de una buena pregunta sería "¿A dónde fuimos a cenar a Minneapolis?" Y el ejemplo de una pregunta incorrecta sería "¿Se pueden comprar manzanas en Tokio?"

**Las respuestas deben coincidir exactamente; así que tenlo en cuenta al elegir una respuesta a tu pregunta. Las mayúsculas importan, por lo que podría considerar incluir una nota como (por ejemplo: use letras mayúsculas, minúsculas).**

Ingrese la pregunta y la respuesta, luego haga clic en el botón "Autenticar".
![image](tool_pidgin36 .png)

Tu amigo tendrá una ventana abierta con la pregunta que se muestra pidiendo la respuesta. Tendrán que responder y hacer clic en el botón "Autenticar". Luego, recibirán un mensaje que les informará si la autenticación fue exitosa.
![image](tool_pidgin37.png)![image](tool_pidgin38.png)

Una vez que su amigo haya completado el procedimiento de autenticación, obtendrá una ventana que le permite saber que la autenticación fue exitosa.
![image](tool_pidgin39.png)

Tu amigo también debe verificar tu cuenta para que ambos puedan estar seguros de que la comunicación es segura. Esto es lo que le gustaría a Akiko y Boris. Observe los iconos verdes "Privado" en la esquina inferior derecha de la ventana de chat.
![image](tool_pidgin40.png)

### 5 Trabajar con otro software

Los mecanismos para verificar la autenticidad debería funcionar entre diferentes software de chat como Jitsi, Pidgin, Adium y Kopete. No es necesario que use el mismo software de chat para usar el chat a través de XMPP y OTR, pero a veces hay errores en el software. Adium, un software de chat para OS X, tiene un error al recibir la verificación de Pregunta y Respuesta. Si encuentra que la verificación de otros está fallando para usted cuando usa la verificación de preguntas y respuestas, verifique si están usando Adium y si puede usar otro método de verificación.
