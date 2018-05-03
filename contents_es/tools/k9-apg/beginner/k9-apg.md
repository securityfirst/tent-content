[Title]: # ()
[Order]: # (0)

# K9 & APG GUÍA DE HERRAMIENTAS

## K9 & APG Guía de herramientas
 Correo electrónico encriptado para Android
 
**Lección para leer:** [Correo electrónico](umbrella://lesson/email)

**Ubicación de descarga:**
- **[Página de inicio de APG](http://www.thialfihar.org/projects/apg/)**
- **[Página de inicio de K-9 Mail](https://code.google.com/p/k9mail)**

**Requisitos del teléfono:**
- Android 1.5 o superior
- APG debe estar instalado antes de instalar K-9 Mail

**Versión utilizada en esta guía:**
- APG 1.1.1
- K-9 5.001

**Licencia:**
- APG: software libre y de código abierto (Gnu GPL v3)
- K-9: Software gratuito y de código abierto (Apache 2.0)

**Otra lectura:**
- [Contraseñas](umbrella://lesson/passwords)  
- [Teléfonos móviles](umbrella://lesson/mobile-phones)   
**Nivel:** Avanzado  
**Tiempo requerido:** 30-40 minutos  

**El uso de K-9 y APG te dará:**
- APG se puede utilizar para cifrar, descifrar y firmar correos electrónicos y archivos individuales localmente en su teléfono.
- Cuando se utiliza APG con K-9, le brinda la posibilidad de utilizar correos electrónicos encriptados fácilmente en su teléfono.

**Android Privacy Guard (APG) para dispositivos Android**
![image](tool_k91.png)

### 1.0 Cómo instalar APG

**Paso 1.** En su dispositivo Android, descargue e instale la aplicación desde **[Google Play aquí](https://play.google.com/store/apps/details?id=org.thialfihar.android. apg)** presionando, "Instalar".
![image](tool_k92.png)

**Paso 2:** Antes de que comience el proceso de instalación, se le pedirá que revise el acceso que la aplicación tendrá en su teléfono. Revisa esto cuidadosamente. Una vez que esté satisfecho con los permisos que se le otorgarán, presione "Aceptar" y la instalación se completará. Si no está de acuerdo con los permisos que se le otorgarán, presione el botón Atrás y la instalación se cancelará.
![image](tool_k93.png)

### 1.1 Gestión de claves

Para encriptar archivos o mensajes la primera vez que inicie APG, se le pedirá que importe claves GPG existentes o que cree una nueva clave pública y privada en su teléfono.
![image](tool_k94.png)

**Nota:** Si desea enviar archivos cifrados o mensajes a otras personas, deberá importar sus claves públicas o decidir una contraseña compartida.

### 1.1.1 Gestión de claves: crea tus claves públicas y privadas

Si aún no tiene su clave GPG pública y privada o desea usar una clave GPG separada para su dispositivo Android, puede usar APG para crearla.

**Paso 1:** Cuando abre APG por primera vez, haga clic en el botón "Crear su propia clave", como se muestra arriba.

**Paso 2:** Espere de 2 a 3 minutos mientras se generan las claves GPG. Podrá asignar su nombre y dirección de correo electrónico a la clave en el siguiente paso.

**Paso 3:** En la siguiente pantalla, a continuación:

- Le recomendamos encarecidamente que proteja sus claves GPG con contraseña. Para hacer esto, presione "Establecer frase de contraseña" y proporcione una contraseña segura. Consulte **[Contraseñas lección](umbrella://lesson/passwords)** sobre la mejor manera de hacerlo;
- Complete su _name, dirección de correo electrónico_;
- Es importante que establezca una fecha de caducidad en las claves GPG, después de lo cual las claves ya no se pueden usar para cifrar archivos.
![image](tool_k95.png)

**Paso 4:** Una vez que toda la información es correcta, toque "Guardar" en la parte superior de la pantalla para volver a la pantalla principal de APG, como se muestra arriba, donde verá una lista de todas sus claves.

### 1.1.2 Gestión de claves - Importar claves desde un archivo

Para usar las claves GPG que creó en otro dispositivo o computadora, o para importar las claves públicas de su contacto:

**Paso 1:** Copie las claves GPG a su dispositivo Android a través de USB o guárdelas del correo electrónico que recibió en el dispositivo Android.

**Paso 2:** En APG, haga clic en el botón "Importar claves".

**Paso 3:** En la siguiente pantalla, haga clic en el botón "Abrir" en la parte superior de la pantalla para abrir un buscador de archivos.

**Paso 4:** Desde el buscador de archivos, seleccione la (s) clave (s) que desea importar.

**Paso 5:** Revise las claves que va a importar y toque "Importar claves seleccionadas" para agregar las claves GPG a APG. Puede decidir qué claves no desea importar desactivando la casilla correspondiente a las claves.
![image](tool_k96.png)

**Paso 6:** Una vez que haya importado todas las claves GPG deseadas, volverá a la pantalla principal donde verá una lista de todas sus claves.
![image](tool_k97.png)

### 1.1.3 Gestión de claves - Importar claves desde el portapapeles

Las claves GPG se pueden enviar en el cuerpo de un correo electrónico en lugar de como un archivo adjunto para importar dicha clave

**Paso 1:** Copie la clave GPG de su correo electrónico en el portapapeles. La imagen a continuación muestra una clave GPG en el cuerpo de un correo electrónico.
![image](tool_k98.png)

**Paso 2:** Abra APG y expanda el menú lateral en cualquier pantalla APG presionando "APG" en la parte superior izquierda de su pantalla.

**Paso 3:** Seleccione "Importar claves" para que aparezca la pantalla de importación de clave.

**Paso 4:** Toque "Keyserver" en la parte superior de la pantalla para mostrar el menú de opciones de importación y seleccione "Importar portapapeles".
![image](tool_k99.png)

**Paso 5:** Toque "Obtener clave del portapapeles" para copiar la clave del portapapeles.

**Paso 6:** Toca "Importar teclas seleccionadas" en la parte inferior de la pantalla para finalizar la importación de la clave en APG
![image](tool_k910.png)

### 1.1.4 Gestión de claves: comparte tu clave pública Como un archivo

Para que sus contactos puedan enviarle correos encriptados, primero deberá enviarles su _public key_

**Paso 1:** Desde la ventana principal de **APG**, toque la entrada de su llave para llevarlo a la pantalla _info_ (como se indicó anteriormente) para su llave GPG.

**Paso 2:** Toque los tres puntos verticales en la esquina superior derecha para mostrar el menú y seleccione "Exportar a archivo".
![image](tool_k911.png)

**Paso 3:** Seleccione la ubicación y el nombre del archivo donde desea guardar su clave pública y presione "OK".
![image](tool_k912.png)

**Paso 4:** El archivo guardado no puede entregarse a sus contactos, por ejemplo, por correo electrónico o mensajería instantánea.

### 1.1.5 Gestión de claves: comparte tu clave pública Desde el portapapeles

**Paso 1:** Desde la ventana principal de APG, toque la entrada de su llave para llevarlo a la pantalla _info_ de su llave GPG.

**Paso 2:** Toque los tres puntos conectados en la parte superior de la pantalla para que aparezcan las opciones para compartir y seleccione "Compartir clave completa".

**Paso 3:** En el siguiente menú, seleccione "Copiar al portapapeles" para copiar su clave pública GPG en el portapapeles.
![image](tool_k913.png)

**Paso 4:** Pegue la clave pública en un correo electrónico o sesión de chat de IM a su contacto.

### 1.1.6 Gestión de claves: verificar identidades

Para asegurarse de que ha recibido la clave pública GPG correcta para su colega y no de alguien que intenta personificarla, es muy importante que verifique las huellas dactilares de las llaves GPG, ya sea en persona o mediante un medio que pueda verificar con quién está hablando. a una llamada de video o llamada telefónica.

**Paso 1:** Desde la ventana principal de **APG**, toque la entrada de su llave para llevarlo a la pantalla _info_ de su llave GPG. Su contacto debería hacer lo mismo y tocar la tecla que tienen para usted.
![image](tool_k914.png)

**Paso 2:** Ubica la línea **Fingerprint** debajo del encabezado ** MASTER KEY ** y lee la cuerda larga de 40 caracteres una línea a la vez.
![image](tool_k915.png)

 **Paso 3:** Su contacto debe verificar que la huella dactilar que leyó sea la huella digital que se muestra para su llave en su teléfono o computadora.
 
 **Paso 4:** Repite los pasos 1 a 3, pero toca la tecla de tus contactos en el primer paso.

### 1.2 Cifrado de mensajes

APG proporciona dos maneras para cifrar archivos en su dispositivo Android. El cifrado de clave pública es la opción deseada para enviar archivos a otras personas, ya que no tendrá que compartir ninguna frase de contraseña con ellos. Sin embargo, deberá recibir la clave pública de cada persona que desee cifrar con anticipación. El cifrado de frase de contraseña puede ser útil para poder descifrar un archivo en una fecha posterior sin la necesidad de tener acceso a una clave pública. Pero este método requiere compartir la frase de contraseña utilizada para encriptar el archivo para descifrarlo más tarde.

El cifrado de mensajes en **APG** puede ser útil si desea almacenar notas cifradas en otra aplicación o enviar correos electrónicos o mensajes cifrados a través de un servicio con el que no puede usar el correo K-9 (por ejemplo, correo web, mensaje de redes sociales, etc...).

### 1.2.1 Cifrado de mensajes - Clave pública

**Paso 1:** Expande el menú lateral en cualquier pantalla ** APG ** presionando "APG" en la parte superior izquierda de tu pantalla.

**Paso 2:** Seleccione "Encriptar" para que aparezca la pantalla de encriptación.

**Paso 3:** Para ver la lista de posibles destinatarios, presione el botón "Seleccionar" con el icono de la persona. ** Nota:** Si desea poder descifrar el mensaje en otro momento, deberá recordar incluirse en la lista de destinatarios.

**Paso 4:** En la pantalla de selección de destinatarios, marque todas las personas que necesitan descifrar el mensaje y presione "Aceptar".
![image](tool_k916.png)

**Paso 5:** Elija cómo encriptar su mensaje. Al tocar "Compartir con ...", podrá enviar el mensaje cifrado a otra aplicación de su teléfono, como un cliente de correo electrónico. Al tocar "Portapapeles" se copiará el mensaje cifrado a su portapapeles, lo que le permite pegar el mensaje en cualquier lugar que pueda pegar, como un foro en línea.

### 1.2.2 Cifrado de mensajes - PassPhrase

**Paso 1:** Expande el menú lateral en cualquier pantalla APG presionando "APG" en la parte superior izquierda de tu pantalla.

**Paso 2:** Seleccione "Encriptar" para que aparezca la pantalla de encriptación.

**Paso 3:** Presione el botones a ambos lados de **CLAVE PUBLICA** para cambiar el tipo de encriptación a PASAPRASE.

**Paso 4:** Ingrese una contraseña segura en los campos provistos.

**Paso 5:** Ingrese el mensaje que desea encriptar
![image](tool_k917.png)

**Paso 6:** Elija cómo usar su mensaje encriptado. Al tocar "Compartir con ...", podrá enviar el mensaje cifrado a otra aplicación de su teléfono, como un cliente de correo electrónico. Al tocar "Portapapeles" se copiará el mensaje cifrado a su portapapeles, lo que le permite pegar el mensaje en cualquier lugar que pueda pegar, como un foro en línea.

**Nota:** Si planea compartir el mensaje cifrado con un contacto, deberá retransmitir la _passphrase_ de forma segura, como en persona. Nunca se debe enviar a nadie por correo electrónico o mensajería instantánea si no está encriptado.

### 1.2.3 Descifrado de mensajes

**Paso 1:** Copie todo el contenido del mensaje cifrado que recibió en la otra aplicación en el portapapeles grabando el mensaje y seleccionando el botón Copiar.

**Paso 2:** Cambie a la aplicación APG y expanda el menú lateral en cualquier pantalla APG presionando "APG" en la parte superior izquierda de su pantalla.

**Paso 3:** Seleccione "Descifrar" para que aparezca la pantalla de encriptación.

**Paso 4:** APG detectará automáticamente que el portapapeles tiene un mensaje cifrado y le pedirá su contraseña GPG, si el remitente usó cifrado de clave pública, o la contraseña del mensaje, si utilizó el cifrado _passphrase_.
![image](tool_k918.png)

**Paso 5:** El mensaje descifrado se mostrará en una ventana de texto dentro de APG.

### 1.3 Cifrado de archivos

Al igual que con el cifrado de mensajes, la clave pública es el método de cifrado preferido, pero el cifrado de contraseñas le permitirá descifrar en un teléfono o computadora que no tenga una clave privada instalada pero que tenga un software APG o GPG.

### 1.3.1 Cifrado de archivos - Clave pública

**Paso 1:** Expande el menú lateral en cualquier pantalla APG presionando "APG" en la parte superior izquierda de tu pantalla.

**Paso 2:** Seleccione "Encriptar" para que aparezca la pantalla de encriptación.

**Paso 3:** Para ver la lista de posibles destinatarios, presione "Seleccionar" con el icono de la persona. **Nota:** Si desea poder descifrar el archivo usted mismo más adelante, deberá recordar incluirse en la lista de destinatarios.

**Paso 4:** En la pantalla de selección de destinatarios, marque todas las personas que desee para poder descifrar el archivo y presione "Aceptar".
![image](tool_k919.png)

 **Paso 5:** Presione el botones a ambos lados de **MENSAJE** para cambiar el tipo de encriptación a **ARCHIVO**.
 
 **Paso 6:** Toque el ícono del archivo abierto para abrir el buscador de archivos y seleccione el archivo que desea encriptar.
![image](tool_k920.png)

**Paso 7:** presiona "Encrypt File" para elegir un nombre de archivo y ubicación para guardar el archivo.
![image](tool_k921.png)

**Paso 8:** Toque "OK" para completar el proceso de encriptación.

### 1.3.2 Cifrado de archivos - PassPhrase

**Paso 1:** Expande el menú lateral en cualquier pantalla APG presionando "APG" en la parte superior izquierda de tu pantalla.

**Paso 2:** Seleccione "Encriptar" para que aparezca la pantalla de encriptación.

**Paso 3:** Presione el
 botones a cada lado de **CLAVE PÚBLICA** para cambiar el tipo de encriptación a **PASAPORTE**
 .
**Paso 4:** Ingrese una contraseña segura en los campos provistos.

**Paso 5:** Presione el
 botones a ambos lados de **MENSAJE** para cambiar el tipo de encriptación a ARCHIVO.

 **Paso 6:** Toque el ícono del archivo abierto para abrir el buscador de archivos y seleccione el archivo que desea encriptar.
![image](tool_k922.png)

**Paso 7:** presiona "Cifrar archivo" para elegir un nombre de archivo y ubicación para guardar el archivo.
![image](tool_k923.png)

**Paso 8:** Toque "OK" para completar el proceso de encriptación.

**Nota:** Si planea compartir el archivo cifrado con un contacto, deberá retransmitir la _passphrase_ de forma segura, como en persona. Nunca se debe enviar a nadie por correo electrónico o mensajería instantánea si no está encriptado.

### 1.3.3 Descifrado de archivos

**Paso 1:** Expande el menú lateral en cualquier pantalla APG presionando "APG" en la parte superior izquierda de tu pantalla.

**Paso 2:** Seleccione "Descifrar" para que aparezca la pantalla de encriptación.

**Paso 3:** Toca el botones a ambos lados de **MENSAJE** para cambiar el tipo de encriptación a **ARCHIVO**.

 **Paso 4:** Toque el icono de abrir archivo para abrir el buscador de archivos y seleccionar el archivo que desea descifrar.
![image](tool_k924.png)

**Paso 7:** presiona "Descifrar", después de lo cual se te solicitará la contraseña de las llaves GPG si se utilizó el cifrado de clave pública o la contraseña del archivo si usaste el cifrado _passphrase_.
![image](tool_k925.png)

**Paso 8:** Toque "OK" para elegir una ubicación para guardar el documento descifrado.
![image](tool_k926.png)

**Paso 9:** Toque "OK" para completar el proceso de descifrado.

* * *

**Correo K-9 con APG**
![image](tool_k927.png)

### 2.0 Cómo instalar _K-9 Mail_

**Nota:** Antes de comenzar a utilizar el Correo K-9, deberá tener una cuenta de correo electrónico, como Gmail, que admita conexiones seguras POP3 o IMAP.

**Paso 1.** En su dispositivo Android, **descargue** y **instale** la aplicación en la [tienda Google Play aquí](https://play.google.com/store/apps/details? id = com.fsck.k9) almacenar tocando "Instalar".
![image](tool_k928.png)

**Paso 2.** Antes de que comience el proceso de instalación, se le pedirá que revise el acceso que la aplicación tendrá en su teléfono. Revisa esto cuidadosamente. Una vez que esté satisfecho con los permisos que se le otorgarán, toque "Aceptar" y la instalación se completará. Si no está de acuerdo con los permisos que se otorgarán, toque el botón Atrás y la instalación se cancelará.
![image](tool_k929.png)

**Paso 3.** Toca "Abrir" para ejecutar la aplicación por primera vez

## 2.1 Cómo configurar el correo K-9

Después de instalar K-9 Mail y ejecutarlo por primera vez, se le presentará una pantalla de bienvenida que describe las características del cliente de correo. Presione "Siguiente" para comenzar la configuración de la cuenta.

Donde sea posible, K-9 Mail intentará configurar automáticamente su cuenta de correo electrónico para usted. Si esto no es posible o si desea tener más control sobre la configuración de la cuenta, también puede configurar manualmente su cuenta.

### 2.1.1 Configuración de cuenta automática

**Paso 1:** Ingrese su dirección de correo electrónico y contraseña de correo electrónico en los campos provistos y toque "Siguiente".
![image](tool_k930.png)

**Paso 2:** **K-9 Mail** se conectará a Internet e intentará obtener la configuración de su cuenta.

**Paso 3:** Una vez que se hayan recuperado las configuraciones, se le pedirá que ingrese su nombre tal como desea que se muestre en todos los correos electrónicos salientes y que le dé un nombre a la cuenta. El nombre de la cuenta le permitirá distinguir entre varias cuentas, en caso de que quiera agregar más. Toca "Listo" para completar la configuración de la cuenta.
![image](tool_k931.png)

**Paso 4:** Correo de K-9 mostrará los cambios en el programa desde la última versión, toque "OK" para cerrar esta ventana y ser llevado a su cuenta de correo.
![image](tool_k932.png)

**Paso 5:** Para asegurarse de que la cuenta funcione en K-9 Mail, envíese un correo electrónico desde su computadora y descárguelo del cliente de correo K-9.

### 2.1.2 Configuración manual de la cuenta

**Paso 1:** Ingrese su dirección de correo electrónico y contraseña de correo electrónico en los campos provistos y toque "Configuración manual".

**Paso 2:** Seleccione el tipo de cuenta que su correo electrónico es (IMAP / POP / Exchange) y toque el botón correspondiente como en la imagen a continuación.

**Nota:** tendrá que consultar la configuración del cliente de correo electrónico en su computadora para saber qué tipo de cuenta utiliza su servidor de correo electrónico.
![image](tool_k933.png)

**Paso 3:** A continuación están las configuraciones del servidor entrante. Si no está seguro, consulte la configuración del cliente de correo electrónico en su computadora. Asegúrese siempre de que _security type_ esté configurado en _STARTTLS_ o _SSL / TLS_. **Nunca** use la opción _none_.
![image](tool_k934.png)

**Paso 4:** **Correo K-9** se conectará a su servidor de correo para verificar si su configuración es correcta. Puede mostrar una advertencia sobre el certificado de su conexión segura. **_¡No ignore esto!_** Esta es la única vez que puede verificar que el certificado realmente pertenece a su servidor de correo. Si ignora esto, no puede estar seguro si no está sujeto a un ataque _Man-in-the-Middle_ y sus comunicaciones podrían ser interceptadas. Puede ver una huella digital SHA-1 al final de la advertencia. O bien **verifique** en su computadora si el certificado instalado de su servidor de correo tiene la misma huella dactilar o busque una forma de verificar el certificado de su servidor de correo directamente de su proveedor.

**Paso 5:** **K-9 Mail** le pide que configure la configuración del servidor saliente. De nuevo, **asegúrese** de que _Security Type_ sea _STARTTLS_ o _SSL / TLS_. Para todas las configuraciones adicionales, **verifique** el cliente de correo electrónico de su computadora o la configuración de su proveedor de correo electrónico.
![image](tool_k935.png)

**Paso 6.** K-9 Mail ahora le pregunta con qué frecuencia desea que sondee automáticamente por correo electrónico. Establezca la opción en _never_ y desmarque _enable push mail_ para esta cuenta, si solo desea recibir correos electrónicos cuando los comprueba manualmente; de lo contrario, deje la configuración tal como está para recibir automáticamente el correo electrónico cuando llegue a su cuenta.
![image](tool_k936.png)

**Paso 7.** Las últimas piezas de información para proporcionar son un apodo para la cuenta de correo electrónico que se mostrará en K-9 Mail y para configurar el nombre que desea que se muestre en todos los correos electrónicos salientes.

**Paso 8:** Para asegurarse de que la cuenta funcione en K-9 Mail, envíese un correo electrónico desde su computadora y descárguelo del cliente de correo K-9.

Recomendamos que use Correo K-9 solo además del cliente de correo electrónico de su computadora. Por lo tanto, es importante que cuando descargue el correo electrónico con su teléfono Android, no elimine el correo electrónico en el servidor, ya que también desea recibir el correo electrónico más adelante con su computadora. De forma predeterminada, K-9 Mail está configurado de esta manera, pero es posible que desee obtener más información acerca de la configuración que se puede encontrar en _accounts_; esto se puede lograr pulsando prolongadamente en la cuenta que acaba de configurar y seleccionando _configuraciones de cuenta_ en el menú. También es posible que desee comprobar la opción _fetching mail_ y _sending mail_ account para la configuración.

### 2.2 Cómo enviar y recibir correos electrónicos encriptados

Uno de los principales beneficios de utilizar K-9 Mail sobre otros clientes de correo electrónico es que le permite enviar y recibir correos electrónicos encriptados de GPG. Antes de que pueda comenzar a enviar y recibir correos electrónicos cifrados, debe asegurarse de tener todas sus claves OpenPGP importadas en APG, como se describe en la sección anterior de APG. Si siguió todos los pasos necesarios en la sección de teclas APG, sus claves serán importadas.

### 2.2.1 Envío de correo electrónico cifrado

**Paso 1:** Desde cualquier pantalla en K-9 Mail, toca el ícono Enviar correo electrónico para iniciar un nuevo correo electrónico.

**Paso 2:** En la pantalla de composición de correo electrónico, agregue su destinatario escribiendo una dirección de correo electrónico o presionando el ícono Agregar destinatario y seleccionando uno de su libreta de direcciones.

**Paso 3:** Habilite el correo electrónico encriptado marcando la casilla junto a _encrypt_.

**Paso 4:** Cuando termine de escribir su correo electrónico, presione el ícono Enviar para enviar.
![image](tool_k937.png)

**Paso 5:** La siguiente pantalla le pedirá que seleccione las claves GPG para encriptar. Sea predeterminado, la clave del destinatario y la suya ya deben estar seleccionadas.

**Nota:** Siempre debe asegurarse de que su clave esté seleccionada para que pueda leer el correo electrónico encriptado que envió.
![image](tool_k938.png)

**Paso 6:** Una vez que se hayan seleccionado todas las claves del destinatario, presione "OK" para enviar el correo electrónico.

**Nota:** Actualmente, K-9 Mail no puede encriptar archivos adjuntos, por lo que deberá cifrar cualquier archivo con APG que desee enviar, antes de redactar el correo electrónico. Esto se explica en la sección de cifrado APG anterior. Para adjuntar los archivos, toque el icono adjunto del clip y seleccione el archivo cifrado (que termina en _.gpg_).

### 2.2.2 Recepción de correo electrónico cifrado

**Paso 1:** Abra su _inbox_ y toque el correo electrónico que desea leer.
![image](tool_k939.png)

**Paso 2:** Toca el botón "Descifrar".
![image](tool_k940.png)

**Paso 3:** Ingrese la contraseña de su clave GPG cuando se le solicite y presione "OK" para descifrar el correo electrónico.
![image](tool_k941.png)


**Nota:** como **Correo de K-9** actualmente no puede descifrar archivos adjuntos cifrados, deberá guardar los archivos adjuntos en su teléfono y descifrarlos con APG, como se explica en la sección de descifrado de APG anterior.
