[Title]: # ()
[Difficulty]: # (Principiante)
[Order]: # (0)

# GUÍA DE LA HERRAMIENTA ADIUM

## Adium & OTR 
Seguridad de mensajería instantánea para Mac 

**Lección para leer: [Enviar un mensaje](umbrella://lesson/sending-a-message)** 
**Ubicación de descarga:** [https://adium.im/](https://adium.im/) 
**Requisitos de computadora** (Adium 1.5 o posterior): Mac OS X 10.6.8 o más reciente, una computadora Macintosh de marca Apple. 
**Versión utilizada en esta guía:** Adium 1.5.9 
**Licencia:** GNU GPL 
**Otra lectura:** [https://pressfreedomfoundation.org/encryption-works](https://pressfreedomfoundation.org/encryption-works);[https://adium.im/help/](https://adium.im/help/) 
**Nivel:** Beginner-Intermediate 
**Tiempo requerido:** 15-20 minutos 

Adium es un cliente de mensajería instantánea de código abierto para OS X que le permite chatear con personas a través de múltiples protocolos de chat, incluidos Google Hangouts, Yahoo! Messenger, chat de Facebook, Windows Live Messenger, AIM, ICQ y XMPP. 

OTR (Off-the-record) es un protocolo que permite a las personas mantener conversaciones confidenciales utilizando las herramientas de mensajería con las que ya están familiarizados. Esto no debe confundirse con "Off the record" de Google, que simplemente deshabilita el registro de chat, y no tiene capacidades de cifrado o verificación. Para los usuarios de Mac, OTR viene incorporado con el cliente Adium. 

OTR emplea cifrado de extremo a extremo. Esto significa que puede usarlo para tener conversaciones sobre servicios como Google Hangouts o Facebook sin que esas compañías tengan acceso a los contenidos de las conversaciones. Esto es diferente de la forma en que Google y AOL usan el término "fuera del registro" para indicar que una conversación no se está registrando; esa opción no encripta tu conversación. 

### ¿Por qué debería usar Adium + OTR? 

Cuando tienes una conversación de chat con Google Hangouts o chat de Facebook en los sitios web de Google o Facebook, ese chat se cifra usando HTTPS, lo que significa que el contenido de su chat está protegido de los piratas informáticos y otros terceros mientras está en tránsito. Sin embargo, no está protegido de Google o Facebook, que tienen las claves de sus conversaciones y puede entregarlas a las autoridades. 

Después de haber instalado Adium, puede iniciar sesión usando múltiples cuentas al mismo tiempo. Por ejemplo, puede usar Google Hangouts, Facebook y XMPP simultáneamente. Adium también te permite chatear usando estas herramientas sin OTR. Como OTR solo funciona si las dos personas lo están usando, esto significa que incluso si la otra persona no lo tiene instalado, puedes chatear con ellos utilizando Adium. 

Adium también te permite hacer una verificación fuera de banda. asegúrese de estar hablando con la persona con la que cree que está hablando y de que no está siendo sujeto a un ataque MITM. Para cada conversación, hay una opción que le mostrará las huellas dactilares clave que tiene para usted y la persona con la que está chateando. Una "huella dactilar de clave " es una cadena de caracteres como "342e 2309 bd20 0912 ff10 6c63 2192 1928, " que se usa para verificar una clave pública más larga. Intercambie sus huellas dactilares a través de otro canal de comunicación, como Twitter DM o correo electrónico, para asegurarse de que nadie interfiera con su conversación. 

### Limitaciones: ¿Cuándo no debería usar Adium + OTR? 

Los tecnólogos tienen un término para describir cuándo un programa o tecnología podría ser vulnerable a un ataque externo: dicen que tiene una gran "superficie de ataque". Adium tiene una gran superficie de ataque. Es un programa complejo, que no se ha escrito con la seguridad como una prioridad principal. Es casi seguro que tiene errores, algunos de los cuales podrían ser utilizados por los gobiernos o incluso las grandes empresas para entrar en las computadoras que lo están usando. Usar Adium para encriptar sus conversaciones es una gran defensa contra el tipo de vigilancia de redirección no focalizada que se usa para espiar las conversaciones de Internet de todos, pero si cree que será atacado personalmente por un atacante con recursos suficientes (como un estado-nación), debería considerar precauciones más estrictas, como el correo electrónico PGP encriptado. 

### Instalación de Adium + OTR en su Mac 

Paso 1: Instale el programa 

Primero, vaya a [https: // adium. im /](https://adium.im/) en su navegador. Elija "Descargar Adium 1.5.9. " El archivo se descargará como .dmg, o imagen de disco, y probablemente se guardará en su carpeta "downloads". 

Haga doble clic en el archivo; eso abrirá una ventana que se ve así: 
![image](tool_adium1.png) 

Mueve el icono de Adium en la carpeta "Aplicaciones " para instalar el programa. Una vez que el programa esté instalado, búsquelo en su carpeta Aplicaciones y haga doble clic para abrirlo. 

Paso 2: configure su(s) cuenta(s) 

En primer lugar, deberá decidir qué herramientas de chat o protocolos quiero usar con Adium. El proceso de instalación es similar, pero no idéntico, para cada tipo de herramienta. Tendrá que saber el nombre de su cuenta para cada herramienta o protocolo, así como su contraseña para cada cuenta. 

Para configurar una cuenta, vaya al menú de Adium en la parte superior de la pantalla y haga clic en "Adium" y luego "Preferencias". Esto abrirá una ventana con otro menú en la parte superior. Seleccione "Cuentas", luego haga clic en el signo "+" en la parte inferior de la ventana. Verá un menú que se ve así: 
![image](tool_adium2.png) 

Seleccione el programa al que desea iniciar sesión. Desde aquí, se le pedirá que ingrese su nombre de usuario y contraseña, o que use la herramienta de autorización de Adium para iniciar sesión en su cuenta. Siga las instrucciones de Adium cuidadosamente. 

### Cómo iniciar un chat OTR 

Una vez que haya iniciado sesión en una o más de sus cuentas, puede comenzar a usar OTR. 

**Recuerde: en orden para tener una conversación usando OTR, ambas personas deben usar un programa de chat que admita OTR.** 

Paso 1: Iniciar un chat OTR 

Primero, identificar a alguien que esté usando OTR e iniciar una conversación con ellos en Adium haciendo doble clic en su nombre. Una vez que haya abierto la ventana de chat, verá un pequeño candado abierto en la esquina superior izquierda de la ventana de chat. Haga clic en el candado y seleccione "Iniciar chat OTR cifrado".

Paso 2: verificar su conexión 

Una vez que haya iniciado el chat y la otra persona haya aceptado la invitación, verá el icono de candado cerrado; así es como usted sabe que su chat ahora está encriptado (¡enhorabuena!) - ¡Pero espere, todavía hay otro paso! 

En este momento, ha iniciado un chat cifrado sin verificar. Esto significa que mientras sus comunicaciones están encriptadas, aún no ha determinado y verificado la identidad de la persona con la que está chateando. A menos que esté en la misma habitación y pueda ver las pantallas de los demás, es importante que verifique las identidades de los demás. (Para obtener más información, lea el módulo EFF en [Verificación de clave](https://ssd.eff.org/en/module/key-verification#overlay=en/node/37/).) 

Para verificar otro la identidad del usuario usando Adium, haga clic de nuevo en el candado y seleccione "Verificar". Se le mostrará una ventana que muestra su clave y la del otro usuario. Algunas versiones de Adium solo admiten la verificación manual de huellas digitales. Esto significa que, utilizando algún método, usted y la persona con la que está chateando deberán verificar que las claves que le muestra Adium coincidan con precisión. 

La manera más fácil de hacerlo es leer en voz alta el uno al otro en persona, pero eso no siempre es posible. Hay diferentes maneras de lograr esto con diversos grados de confiabilidad. Por ejemplo, puede leer sus claves en voz alta entre sí en el teléfono si reconoce las voces de los demás o las envía utilizando otro método verificado de comunicación, como PGP. Algunas personas publican su clave en su sitio web, cuenta de Twitter o tarjeta de presentación. 

**Lo más importante es que verifique que cada letra y dígito coincidan perfectamente.** 

Ahora que ha iniciado una chat encriptado y verificado la identidad de su compañero de chat, hay una cosa más que debe hacer. Desafortunadamente, Adium registra sus chats cifrados OTR de forma predeterminada, guardándolos en su disco duro. Esto significa que, a pesar de que están encriptados, se guardan en texto sin formato en su disco duro. 

Para desactivar el registro, haga clic en "Adium" en el menú en la parte superior de la pantalla, luego "Preferencias". En la nueva ventana, seleccione "General" y luego desactive "Registrar mensajes" y "Registrar chats asegurados por OTR". Su configuración debería verse así: 
![image](tool_adium3.png) 

También, cuando Adium muestra notificaciones de mensajes nuevos, el contenido de esos mensajes puede ser registrado por el Centro de notificaciones OS X. Esto significa que, si bien Adium no deja rastros de sus comunicaciones en su propia computadora o la de su corresponsal, la versión de OS X, o la de su computadora, puede conservar un registro. Para evitar esto, es posible que desee deshabilitar las notificaciones. 

Para ello, seleccione "Eventos" en la ventana de Preferencias, y busque las entradas que digan "Mostrar una notificación". Para cada entrada, amplíela haciendo clic en el triángulo gris, y luego haz clic en la línea recién expuesta que dice "Mostrar una notificación", luego haz clic en el ícono de menos ("-") en la esquina inferior izquierda para quitar esa línea. Si eres preocupado por los registros que quedan en su computadora, también debe activar el cifrado de disco completo, lo que ayudará a proteger esta información de terceros sin su contraseña. 
![image](tool_adium4.png)