[Title]: # ()
[Order]: # (0)

# GUÍA DE HERRAMIENTAS JITSI

## Guía de herramientas Jitsi
Seguridad de audio, video y mensajería instantánea

**Lección para leer: [Hacer una llamada](umbrella://lesson/making-a-call)**
**Ubicación de descarga:** [https://jitsi.org/Main/Download](https://jitsi.org/Main/Download)
**Requisitos de computadora** Todas las versiones de Windows, Mac OS X, Ubuntu, Linux
**Versión utilizada en esta guía:** Jitsi 2.4
**Licencia:** Software libre y de código abierto
**Nivel:** Principiante
**Tiempo requerido:** 15-20 minutos

### 1.1 Introducci

**El uso de Jitsi le brindará:**
- Una alternativa segura a Skype que encripta llamadas, mensajes y video desde su computadora a la computadora del destinatario.
- La capacidad de registrar varias cuentas que ya tiene (como Facebook, MSN, Google Talk o Yahoo Messenger) con Jitsi y usarlas para comunicarse en ellas simultáneamente.
- La capacidad de comunicarse de forma segura y simultánea con otros programas recomendados en esta aplicación, como Pidgin, Adium y ChatSecure.

### 2.1 Cómo instalar Jitsi

Para instalar Jitsi, realice los siguientes pasos:

**Paso 1.** Haga doble clic en "jisi-2.4-latest-x86.exe" ; el cuadro de diálogo _Open File - Security Warning_ puede aparecer. Si lo hace, haga clic en "Siguiente" para activar la pantalla _Windows Installer_, seguido de la ventana _Welcome to Jitsi Setup Wizard_.

**Paso 2.** Haga clic en "Siguiente" para activar el _End User Ventana Acuerdo de licencia; marque la opción _Acepto los términos en el Acuerdo de licencia_ para habilitar el botón _Siguiente_ y luego haga clic en "Siguiente" para activar la ventana _Destination Folder_.

**Paso 3.** Haga clic en "Siguiente" para active la ventana _Additional Tasks_ y acepte la configuración predeterminada tal como se muestra.

**Nota:** La activación de la opción _Auto-start cuando la computadora reinicia o reinicia_ puede ralentizar la función general de su computadora, especialmente si ya tiene múltiples aplicaciones configuradas para ejecutarse cuando se inicia el equipo.

**Paso 4.** Haga clic en "Siguiente" para activar la ventana _Ready to Install Jitsi_ y luego en "Install" para activar la ventana _Installing Jitsi_ mostrando la barra de progreso de la instalación.

**Paso 5.** Haga clic en "Finalizar" para completar el proceso de instalación y ejecute automáticamente la ventana **Jitsi** _Sign in_ de la siguiente manera:
![imagen](tool_jitsi1.png)

**Nota:** En algunos casos, la instalación y el inicio de Jitsi por primera vez desencadenan una pantalla de aviso de _Windows Security Alert_, Como se muestra abajo.

**Paso 6.** Seleccione las casillas de verificación de redes **Privadas** y **Públicas**, y luego haga clic en **_Allow access_** para ver la ventana _Jitsi Sign in window_ o la ventana principal de la interfaz de usuario.
![image](tool_jitsi2.png)

### 2.2 Cómo agregar cuentas en Jitsi

Tenga en cuenta que incluso con el cifrado de Jitsi, los proveedores de cuenta como Google o Facebook están supervisando el hecho de que usted es comunicarse (y tal vez con quién se está comunicando), y puede compartir esta información con terceros, como corporaciones o gobiernos. Por lo tanto, tal vez sea mejor evitar el uso de esas cuentas para una comunicación muy sensible incluso con el cifrado de Jitsi.

### 2.2.1 Cómo agregar una cuenta de Gmail/Google

**Nota:** El ejemplo que sigue se basa en una cuenta de Google Talk, el proceso de configuración para los otros protocolos de comunicación es similar. Las comunicaciones o algunas características de cifrado pueden no funcionar entre usuarios de diferentes proveedores de cuentas (como Facebook, Gmail, Yahoo, etc.). Sin embargo, deberían funcionar cuando se comuniquen entre dos cuentas del mismo proveedor.

**Paso 1.** Seleccione **Iniciar > Jitsi** o haga doble clic en el icono del escritorio de Jitsi para abrir Jitsi.

**Paso 2.** En la ventana _sign in_, ingrese el nombre de usuario y la contraseña de la cuenta de Gmail que desea utilizar para fines de chat, de modo que se asemeje a lo siguiente:
![image](tool_jitsi3.png)

**Nota:** Puede agregar varias cuentas usando diferentes protocolos al mismo tiempo.

**Paso 3.** Haga clic en "Iniciar sesión" para activar la ventana de chat de su cuenta.

**Nota:** Si cerró _Sign in_ window, o si desea agregar otra cuenta, puede agregarlo seleccionando **_File > Agregar nueva cuenta ..._** menú. En la nueva ventana, seleccione **Red** como _Google Talk_ y escriba el nombre de usuario y la contraseña de la cuenta de Gmail como se muestra en la imagen a continuación:
![image](tool_jitsi4.png)

Para verificar que ha registrado su cuenta de Gmail con Jitsi, realice los siguientes pasos:

**Paso 1.** Seleccione **Herramientas > Opciones** en el menú para activar la siguiente ventana:
![image](tool_jitsi5.png)

**Nota:** Si usa la verificación en dos pasos para proteger el acceso a su cuenta de Gmail, cuando intente iniciar sesión desde Jitsi con su contraseña habitual, es posible que vea un mensaje como el que se muestra a continuación. . Para iniciar sesión usando Jitsi, deberá generar una "contraseña específica de la aplicación ". Consulte las [instrucciones de cómo hacerlo](https://support.google.com/accounts/answer/185833?hl=es) de Google.

### 2.2.2 Registro de una nueva cuenta Jabber/XMPP o SIP y agregarlo a Jitsi


Jabber/XMPP y SIP son estándares abiertos de texto y comunicación de voz. Hay muchos servidores que ofrecen cuentas gratuitas que puedes usar con Jitsi. A continuación, le recomendamos algunos de los servidores que podría usar para la comunicación confidencial.

- **Riseup.net** Cuenta Jabber/XMPP

Si tiene una cuenta en el servicio de correo electrónico seguro de Riseup.net (ubicado en EE. UU.), puede usar esta cuenta también para comunicarse a través de la red Jabber/XMPP al agregar esta cuenta a Jitsi, consulte a continuación cómo agregar la cuenta Jabber/XMPP existente.

- **Jabber.ccc.de** y otras cuentas Jabber/XMPP

Puede registrar una cuenta en Jabber. servidor ccc.de (ubicado en Alemania) siguiendo los pasos:

**Paso 1.** En Jitsi, seleccione **_ Archivo > Agregue una nueva cuenta..._** en el menú. En la nueva ventana, seleccione **_Red: XMPP_** y marque **_Crear una nueva cuenta XMPP_** option_. En _*Servidor_, escriba jabber.ccc.de, escriba el nombre de usuario XMPP que desea crear y complete los campos _Password_ y _Confirm_ password para que se parezca a lo siguiente:
![image](tool_jitsi6.png)

**Paso 2.** Haga clic en **Agregar**. Después de un registro exitoso, se le mostrará una ventana similar a la anterior.

Si el nombre de usuario que solicitó ya lo tomó otra persona, el proceso de registro fallará con el mensaje _No hemos podido crear su cuenta debido al siguiente error : No se pudo confirmar data_. Puede volver a intentarlo repitiendo el proceso y seleccionando un nombre de usuario diferente.

**Tenga en cuenta** que si no inicia sesión en su jabber.ccc.de durante más de 12 meses, su cuenta se eliminará automáticamente del el servidor y el nombre de usuario estarán disponibles para su registro por otras personas.

- ** ostel.co ** Cuenta SIP

**Las cuentas SIP** no pueden registrarse desde el programa Jitsi. El servidor **ostel.co** (ubicado en EE. UU.) Ofrece [registro en su página web](https://ostel.co/users/sign_up). Seleccione un nombre de usuario, una contraseña y proporcione su dirección de correo electrónico existente y haga clic en el botón _Arreglar_ en la página web. Después de un registro exitoso regrese al programa Jitsi. Seleccione **_Archivo > Agregue una nueva cuenta ..._** en el menú, seleccione **Red: SIP**, ingrese su nombre de usuario (por ejemplo, terence.the.tester@ostel.co) y la contraseña que creó durante el registro web y haga clic en **_Añadir_**. Consulte la siguiente imagen para referencia:
![image](tool_jitsi7.png)

- **Agregar una cuenta Jabber/XMPP o SIP existente a Jitsi**

Si ya tiene una cuenta Jabber/XMPP o SIP, puede agregarlo a Jitsi seleccionando **_Archivo > Agregar nueva cuenta ..._** en el menú y seleccionando la Red apropiada (ya sea XMPP o SIP dependiendo del tipo de cuenta).

2.2.3 Cómo agregar una cuenta de Facebook

Facebook tiene dos configuraciones que puede necesitar cambiar antes de que Jitsi pueda conectarse a su Chat de Facebook.

- **Nombre de usuario de Facebook**

Facebook requiere un nombre de usuario para Jitsi para conectarse al chat de Facebook . Muchos usuarios de Facebook ya tienen un nombre de usuario. Para verificar su nombre de usuario, inicie sesión en su cuenta de Facebook: su nombre de usuario es lo que aparece en la barra de direcciones de su navegador después de _https://www.facebook.com/_ cuando ve su línea de tiempo o página. Su nombre de usuario también se encuentra en su dirección de correo electrónico de Facebook para su cuenta personal (por ejemplo: nombredeusuario@facebook.com). Puede ver o cambiar el nombre de usuario u obtener uno yendo a la sección _Account Settings > General_ o visitando [https://www.facebook.com/username](https://www.facebook.com/username). Para establecer el nombre de usuario, Facebook puede solicitarle la verificación de su cuenta, que puede requerir el envío de un SMS a un número de teléfono móvil que deberá proporcionar a Facebook en el proceso de verificación.

- **Configuración de la aplicación**

Facebook "plataforma de aplicaciones" debe activarse antes de que ** Jitsi ** pueda conectarse al chat de Facebook. Visite la sección _Account Settings > Apps_ de Facebook y verifique que la configuración de las aplicaciones que usa esté activada. Esto activa "application platform" por tu cuenta. 

**Nota** that that turning Facebook's "application platform" opens up much of your Facebook data to third-party application developers. 
Esta información está disponible no solo para las aplicaciones de Facebook que usa, sino también para las aplicaciones de Facebook que usa cualquiera de sus amigos. Después de activar la "plataforma de aplicaciones" de Facebook, asegúrese de verificar la configuración en "Aplicaciones que otros usan ". Esta configuración le permite ocultar información personal de las aplicaciones utilizadas por sus amigos. Desafortunadamente, Facebook no ofrece configuraciones para ocultar toda la información personal. Ciertas categorías de información (como la lista de amigos, el sexo o la información que ha hecho público) son visibles siempre que la "plataforma de aplicaciones" de Facebook esté activada "en ". Depende de usted determinar si esta es una compensación aceptable de su privacidad.

Ahora está preparado para agregar su cuenta de Facebook a Jitsi. Para ello, siga los pasos a continuación:

**Paso 1.** Desde el menú principal, seleccione **_Archivo > Agregar nueva cuenta ..._**

**Paso 2.** En el diálogo Agregar cuenta nueva, el menú **Red** seleccione _Facebook_, ingrese su nombre de usuario y contraseña y haga clic en **"Agregar "**
![imagen](tool_jitsi8.png)

### 2.3 Cómo cambiar la contraseña de la cuenta con Jitsi

Es un elemento importante de seguridad saber cómo cambiar la contraseña de cada cuenta que tiene. Muchas de las cuentas que puede usar con Jitsi ofrecen cambiar la contraseña como parte de su configuración, a la que se puede acceder a través de la interfaz web. Sin embargo, algunas cuentas Jabber/XMPP y SIP no tendrán ninguna interfaz web para administrarlas. Puede cambiar la contraseña de esa cuenta usando Jitsi siguiendo los pasos a continuación:

**Paso 1.** Seleccione **_Herramientas > Opciones_** en el menú, seleccione la pestaña **_Cuentas_**

**Paso 2.** Haga clic en el botón **_Editar_** en la parte inferior para activar una nueva ventana.

**Paso 3.** Haga clic en **_Cambiar la contraseña de la cuenta_**
para activar _Cambiar cuenta contraseña_ ventana .


Paso 4.** Ingrese una nueva contraseña y vuelva a ingresar la contraseña y haga clic en el botón **_OK_** para cerrar esta ventana.

**Paso 5.** Cierre el Asistente de registro de cuenta.

### 2.4 Cómo configurar Jitsi para mejorar su seguridad

### 2.4.1 Deshabilitar y eliminar el historial de llamadas y chat

Jitsi almacena de forma predeterminada información sobre las llamadas de voz/video entrantes y salientes y el historial de sus chats de texto: todos los mensajes que envió y recibió. Puede acceder a llamadas de voz/video haciendo clic en el ícono del reloj en la ventana principal de Jitsi:
![image](tool_jitsi9.png)

Puede ver el historial de chat de texto haciendo clic en el ícono del temporizador de huevo en la ventana de chat de texto mientras chateas con un contacto:
![image](tool_jitsi10.png)
Incluso si encriptas el chat de texto con OTR todos los mensajes de texto que envías y recibes se almacenan en tu computadora en formato de texto abierto.


Para evitar que Jitsi recopile esta información (y elimine datos ya recopilados), usted y su contacto deben seguir los siguientes pasos.

**Deshabilitar Jitsi para recopilar la información:**

**Paso 1.** Seleccione **_Herramientas > Opciones_** en el menú, seleccione la pestaña **_General_** y desmarque la opción **_Registrar historial de chat_**.

**Paso 2.** en la ventana _Options_, primero **seleccione la pestaña Advanced**, luego **seleccione la sección _Logging_**, y luego **desmarque la opción _Enable packet logging_** como se muestra a continuación:
![image](tool_jitsi11.png)

Tus cambios entrarán en vigencia después reinicia Jitsi.

**Para eliminar la información ya recopilada sobre sus llamadas y mensajes de texto:**

**Paso 1.** Salga de Jitsi.

**Paso 2.** Eliminar toda la carpeta del historial de registros _history_ver1.0_ de la carpeta del perfil de usuario de Jitsi. Puede eliminar una subcarpeta de _history_ver1.0_ si desea deshacerse solo de parte del historial. La ubicación de las carpetas _user profile_ y _log history_ depende del sistema operativo:

- En Windows XP y versiones anteriores, esta se encuentra en _C:\Documents and Settings\&lt;Windows login/user name&gt;\Application Data\Jitsi\history_ver1.0_
- En Windows Vista, 7, 8, esto es _C:\Users\&lt;Windows login/user name&gt;\AppData\Roaming\Jitsi\history_ver1.0_
- Mac OS X: desde su carpeta de inicio _~/Library/Application Support/Jitsi/history_ver1.0_
- Linux: desde su carpeta de inicio _~/.jitsi/history_ver1.0_

Vea la [Lección de eliminación segura](umbrella://lesson/safely-deleting) para obtener más información sobre cómo deshacerse de la información de forma segura.

### 2.4.2 Requerir mensajes privados cuando el chat de texto

Se recomienda configurar Jitsi para que requiera mensajes de texto privados y encriptados usando cifrado OTR siempre que sea posible. Para ello, seleccione **_Herramientas > Opciones_** en el menú, seleccione la pestaña **_Seguridad_**, seleccione la pestaña **_Chat_ y marque
_Requiera mensajes privados_** en la parte inferior de la pantalla.

### 2.4.3 Proteger las contraseñas de sus cuentas con la contraseña maestra

Es mejor no dejar que Jitsi recuerde las contraseñas de sus cuentas. Si decide lo contrario por facilidad de uso, cualquiera que tenga acceso a su computadora podrá iniciar sesión en sus cuentas simplemente iniciando Jitsi. También será posible ver sus contraseñas en la ventana de Opciones. Por lo tanto, **se recomienda encarecidamente** proteger las contraseñas de sus cuentas con una buena contraseña maestra. Una vez que configure la contraseña maestra, Jitsi se lo preguntará al iniciar el programa.

**Paso 1.** Abra la ventana de Opciones seleccionando **_Herramientas > Opciones_** en el menú, seleccione la **_Ficha Seguridad_** y **_Contraseñas_** subpestaña, y verificación **_Usar una contraseña maestra_** para activar la ventana **_Contraseña maestra_**.

**Paso 2.** En el nueva ventana, ingrese su contraseña. Para obtener más información sobre cómo crear una contraseña segura, consulte **[Clase de contraseña](umbrella://lesson/passwords)**.

**Paso 3. Haga clic en _OK_** para confirmar la contraseña y activar una nueva ventana que debería decir **_Contraseña maestra configurada con éxito_**. Haga clic en "**OK**" para cerrarlo y vuelva a la ventana _Options_ que se parecerá a continuación:
![image](tool_jitsi12.png)


**Nota:** The **_Change Master El botón Contraseña_** le permite cambiar la contraseña maestra y el botón **_Contraseñas guardadas ..._** le permite acceder a la lista de contraseñas recordadas por Jitsi y eliminarlas si es necesario.

### Jitsi - Agregar contactos y comunicación de texto & voz

### 3.1 Agregar contactos (amigos) a Jitsi

Después de agregar al menos una cuenta a Jitsi e iniciar sesión, estará listo para agregar sus contactos y comunicarse con ellos.

**Paso 0.** Abra la ventana principal de Jitsi seleccionando **_Iniciar > Jitsi_** o haciendo doble clic en el ícono del escritorio de Jitsi.

**Paso 1.** Seleccione **_Archivo > Agregar contacto ..._** que abrirá la siguiente ventana:
![image](tool_jitsi13.png)

**Paso 2.** Seleccione a cuál de sus cuentas le gustaría agregar este contacto a (por ejemplo _terance.the.tester@jit.si_).

**Opcional:** También puede agregar el contacto a un grupo entre tus otros contactos Sin embargo, primero debes crear el grupo. Para ello, seleccione **_Archivo > Crear grupo ..._** en el menú).

Escriba el nombre de usuario o la dirección de su contacto en el campo **_ID o Número_** (por ejemplo, _sally.the.doer@jit.si_).

Puede elegir el nombre o apodo para el contacto, que será visible en su lista de contactos en la ventana principal de Jitsi; escríbalo en el campo **_Nombre para mostrar_**.

**Paso 3.** Haga clic en _Add_ para cerrar la ventana _Añadir contacto_ y regrese a la ventana principal de Jitsi. En su lista de contactos, ahora verá su nuevo contacto agregado con la nota "Esperando autorización ".

**Paso 4.** Cuando su contacto (sally.the.doer@jit.si) inicie sesión en su cuenta, una ventana emergente le informará que ha solicitado agregarla a su lista de contactos:

Tu contacto tiene la opción de seleccionar la opción _Ignore_, en cuyo caso su solicitud continuará esperando la autorización; _Deny_, en cuyo caso recibirá información de que su solicitud fue rechazada; y _Autorizar_, en cuyo caso recibirá información de que su contacto ha aceptado su solicitud de autorización, y la entrada de su contacto en su lista de contactos se activará.

### 3.2 Chat de texto (Mensajería instantánea) con encriptación OTR

Ahora que agregó y autorizó su contacto, puede hacer clic en su nombre en la lista de contactos e iniciar conversaciones de texto, llamadas de voz o video y compartir el escritorio, seleccionando el ícono correspondiente debajo de su nombre:
![image](tool_jitsi14.png)

Paso 1. Ahora exploraremos una de las características más importantes de Jitsi: la posibilidad de chatear con texto de forma segura, encriptando sus mensajes con OTR. OTR funciona de manera similar a GPG/PGP descrito en otros capítulos de este kit de herramientas. Al igual que con PGP, antes de que usted y su contacto puedan encriptar sus comunicaciones, ambos necesitan configurar Jitsi para generar sus claves de cifrado. Puede hacerlo seleccionando el menú **_Herramientas > Opciones_** y seleccionando la pestaña **_Seguridad_** y **_Chat_**. Luego verá una ventana similar a la que se muestra en la imagen a continuación:
![image](tool_jitsi15.png)

**Paso 2.** Luego, haga clic en el botón **_Generate_**. Como resultado, verá la huella digital de la clave que se ha generado:
![image](tool_jitsi16.png)

Se genera una clave por cuenta. Solo necesita hacer esto de nuevo si agrega una cuenta nueva o instala Jitsi en otro dispositivo y no mueve las claves existentes hacia ella.

Ahora está listo para comunicarse:

**Paso 3.** Seleccione un contacto de la ventana principal de Jitsi y haga clic en el ícono _send mensaje_ (primero desde la izquierda debajo del nombre del contacto) para abrir una ventana de chat de texto:
![image](tool_jitsi17.png)

Note el chat _Encrypt con Icono OTR_, el candado abierto en el lado superior derecho de la ventana. Este símbolo discreto le informa si el chat está encriptado o no. ¡Ahora el candado está abierto (hay un espacio pequeño entre el asa y el cuerpo del candado!).

**Paso 4.** Haga clic en **_Encrypt chat with OTR_** icon. Tenga en cuenta los cambios en la ventana:
![image](tool_jitsi18.png)


Observe que el candado ahora está bloqueado. Esto significa que cualquier mensaje que usted y su contacto se envíen se cifran. Tenga en cuenta el mensaje de que se trata de una conversación _ privada no autenticada y que debe _autenticar_ sally.the.doer@jit.si.

**Paso 5.** Haga clic en el enlace **_autentique sally.the.doer@jit .si_** para abrir la ventana _Authenticate Buddy_:
![image](tool_jitsi19.png)

Tenga en cuenta el mensaje que lo anima a comparar las huellas dactilares de sus teclas con su contacto sobre otro canal (no este chat de texto) . Al hacer esto, puede estar más seguro de que se está comunicando con su contacto y no con otra persona. Una buena opción para las comparaciones clave es hacerlo cara a cara, o a través de video o comunicación de voz, ya que proporcionan medios más fáciles para autenticar la identidad de la otra persona. Después de comparar las huellas dactilares, seleccione la opción **_He verificado_** la huella digital en el menú desplegable y haga clic en **_Autenticar compinche_**:
![image](tool_jitsi20.png)

Cerrar el _Authenticate La ventana Buddy_ le devuelve a la ventana de chat.
![image](tool_jitsi21.png)

Tenga en cuenta que el candado ya no incluye el triángulo naranja con el signo de exclamación blanco. Esto significa que ha autenticado su contacto.** La autenticación debe hacerse solo una vez por contacto.** Si el triángulo con signo de exclamación regresa, significa que estás chateando con alguien que aún no has autenticado. Esto puede suceder cuando su contacto se mueve a otro dispositivo con otra clave de cifrado (otra instalación de Jitsi, u otro programa OTR habilitado, etc.). En este caso, deberá volver a autenticarse entre sí para asegurarse de la identidad de la persona con la que se comunica.

Jitsi le permite chatear por texto con más de una persona al mismo tiempo. El cifrado OTR solo funcionará cuando chatee con una persona.

### 3.3 Chat de voz y video con encriptación ZRTP

Jitsi ofrece chats de voz y video que se pueden encriptar independientemente con un estándar abierto llamado ZRTP. Para iniciar el chat, debe

**Paso 1.** Haga clic en el contacto en la lista de contactos de Jitsi y haga clic en la voz (segundo icono de la izquierda debajo del nombre del contacto) o video (tercero) . Aparecerá una nueva ventana que indica que Jitsi está estableciendo la conexión:
![image](tool_jitsi22.png)

Tu contacto verá una notificación de llamada entrante.

**Paso 2.** Si tu contacto acepta la llamada recibirás información de que estás conectado:
![image](tool_jitsi23.png)

**Nota** el candado rojo abierto. Esto significa que su llamada aún no está encriptada con ZRTP.

**Paso 3.** Espere ... Sus programas y los de su contacto están estableciendo una conexión encriptada, que puede tomar un momento. Si tienen éxito, verá que las letras _zrtp_ aparecen sobre un fondo naranja con un candado cerrado como se muestra a continuación. Si no logran establecer una conexión, aún puedes chatear pero sin encriptar. Puede desconectar, reiniciar Jitsi e intentar nuevamente para ver si esta vez los programas se conectarán con encriptación. ZRTP puede no funcionar en llamadas entre cuentas de diferentes proveedores (como entre Google y Jit.si).
![image](tool_jitsi24.png)

**Paso 4.** Observe la sección debajo de las letras _zrtp_ y candado con el mensaje "Comparar con el compañero" seguido de 4 caracteres. Lee estas cartas a tu contacto y pregunta si ella ve los mismos personajes. Si lo hace, significa que su comunicación está encriptada y nadie está interfiriendo con ella. Puede hacer clic en **_Confirmar_**. El campo naranja _zrtp_ se pondrá verde:
![image](tool_jitsi25.png)

**Paso 5.** Puede cerrar la sección negra de confirmación de la ventana haciendo clic en el signo x blanco en la parte superior parte derecha de la sección negra:

Jitsi te permite hablar y chatear por video con más de una persona. Tenga en cuenta que con esta comunicación, el cifrado ZRTP se puede utilizar entre el iniciador de la llamada y otras partes, pero no entre las partes.