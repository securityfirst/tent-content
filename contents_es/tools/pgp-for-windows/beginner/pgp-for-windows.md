[Title]: # ()
[Order]: # (0)

# PGP PARA WINDOWS GUÍA DE HERRAMIENTAS PARA PC

## PGP para Windows PC Guía de herramientas
Email encriptado para Windows

**Lección para leer:** [Correo electrónico](umbrella://lesson/email)  
**Ubicación de descarga:**
- GPG4Win
- Mozilla Thunderbird
- Enigmail

**Requisitos de computadora:** Una conexión a Internet, una computadora con Mac OS X, una cuenta de correo electrónico  
**Versión utilizada en esta guía:**
- Windows: Windows 7 Ultimate
- Mozilla Thunderbird 24.6.0
- Enigmail 1.7
- GPG4Win 2.2.1

**Licencia:** Software libre; combinación de licencias de Software Libre  
**Nivel:** Avanzado  
**Tiempo requerido:** 30-60 minutos  

**El uso de PGP le dará:**
- La capacidad de proteger su correo electrónico comunicaciones de ser leído por cualquier persona, excepto sus destinatarios previstos.
- La capacidad de demostrar que un correo electrónico provino de una persona en particular, en lugar de ser un mensaje falso enviado por otro remitente (de lo contrario, es muy fácil que se fabrique el correo electrónico). Ambas son defensas importantes si está siendo objeto de vigilancia o desinformación.

### 1.0 Antes de comenzar

Para usar Pretty Good Privacy (PGP), deberá instalar algún software adicional que lo trabaja con tu programa de correo electrónico actual. También necesitarás crear una clave privada, que mantendrás en privado. La clave privada es lo que usará para descifrar los correos electrónicos que se le envían, y para firmar digitalmente correos electrónicos que envíe para mostrar que realmente provienen de usted. Finalmente, aprenderá cómo distribuir su clave pública, una pequeña porción de información que otros necesitarán saber antes de poder enviarle correos encriptados, y que pueden usar para verificar los correos electrónicos que envíe.

**Nota que ambos extremos de la conversación por correo electrónico deben estar usando un software compatible con PGP para que funcione.**

La gente normalmente usará esto solo en sus propios dispositivos personales, no en dispositivos compartidos. Afortunadamente, PGP está disponible para la mayoría de las computadoras de escritorio y dispositivos móviles, y puede indicarles estas guías para ayudarlos a configurar su propia versión. Esta guía es para usuarios de Windows.

### 1.1 Información general

Para usar PGP para intercambiar correos electrónicos seguros, debe unir tres programas: GPG4Win (GNU Privacy Guard para Windows conocido como GnuPG), Mozilla Thunderbird y Enigmail.

- GnuPG es el programa que realmente encripta y descifra el contenido de su correo.
- Mozilla Thunderbird es un cliente de correo electrónico que le permite leer y escribir correos electrónicos sin usar un navegador.
- Enigmail es un complemento de Mozilla Thunderbird que lo une todo.

**Nota! Lo que esta guía enseña es cómo usar PGP con Mozilla Thunderbird, un programa cliente de correo electrónico que realiza una función similar a la de Outlook. Puede tener su propio programa de software de correo electrónico favorito (o utilizar un servicio de correo web como Google Mail o Outlook.com). Esta guía no le dirá cómo usar PGP con estos programas. Puede optar por instalar Thunderbird y experimentar con PGP con un nuevo cliente de correo electrónico, o puede investigar otras soluciones para usar PGP con su software habitual. Todavía no hemos encontrado una solución satisfactoria para estos otros programas.**

**El uso de PGP no encripta completamente su correo electrónico: la información del remitente y del receptor aún no está encriptada, al igual que la línea de asunto.**

Encifrado la información del remitente y del receptor no es posible en el sistema de correo electrónico existente. Lo que le ofrece el uso de Mozilla Thunderbird con el complemento Enigmail es una manera fácil de encriptar el contenido de su correo electrónico. Alguien que espíe sus correos electrónicos puede ver las identidades de las personas con las que se comunica y cuando las envía por correo electrónico.

Primero descargará todo el software necesario, lo instalará y luego finalizará con la configuración y el uso.

### 2 Descarga del software

### 2.1 Obtención de GPG4Win

Puede obtener GnuPG (también conocido como GPG) en Windows descargando el instalador pequeño desde la página de descarga de GPG4Win.
![image](tool_pgpwin1.png)

Haga clic en la versión más reciente de GPG4Win con el componente GnuPG solamente (Vanilla o Light) para descargar el instalador GPG.

**Nota: Esta versión de GPG está disponible solo en un sitio web que ofrece "http" descargas, no seguras "https" descargas. Si le preocupa que una organización que puede alterar su conexión a Internet pueda vigilarlo, puede investigar soluciones más drásticas, como descargar y ejecutar Tails, un sistema operativo seguro que reemplaza a Windows.**

Muchos navegadores le solicitarán que confirme si desea descargar este archivo. Internet Explorer 11 muestra una barra en la parte inferior de la ventana del navegador con un borde naranja.

Para cualquier navegador, lo mejor es guardar primero el archivo antes de continuar, por lo que _haga clic en el botón "Guardar"_. De forma predeterminada, la mayoría de los navegadores guardan los archivos descargados en la carpeta de Descargas.

### 2.2 Obteniendo Mozilla Thunderbird

Vaya al sitio web de Mozilla Thunderbird.
![image](tool_pgpwin2.png)

Haga clic en el botón verde etiquetado "Descarga gratuita de Thunderbird. "

El sitio web de Mozilla Thunderbird habrá detectado su idioma preferido. Si desea utilizar Thunderbird en otro idioma, haga clic en el enlace "Other Systems & Languages" y realice su selección desde allí.

Muchos navegadores le solicitarán que confirme si desea descargar este archivo. Internet Explorer 11 muestra una barra en la parte inferior de la ventana del navegador con un borde naranja.
![image](tool_pgpwin3.png)

Para cualquier navegador, es mejor guardar primero el archivo antes de continuar, haga clic en "Guardar" botón. De forma predeterminada, la mayoría de los navegadores guardan los archivos descargados en la carpeta Descargas.

### 2.3 Obtención de Enigmail

Puede obtener Enigmail del sitio web de Enigmail.
![image](tool_pgpwin4.png)

Many los navegadores le pedirán que confirme si desea descargar este archivo. Internet Explorer 11 muestra una barra en la parte inferior de la ventana del navegador con un borde naranja.
![image](tool_pgpwin5.png)
Para cualquier navegador, lo mejor es guardar primero el archivo antes de continuar, haga clic en el botón "Guardar "botón. De forma predeterminada, la mayoría de los navegadores guardan los archivos descargados en la carpeta de descargas.

Después de descargar Enigmail, GPG4Win y Mozilla Thunderbird debe tener tres archivos nuevos en su carpeta de descargas:
![image](tool_pgpwin6.png)

### 3 Instalación del software

### 3.1 Instalación de GPG4Win

Mantenga abierta la ventana del Explorador de Windows y haga doble clic en gpg4win-xxx-xxxexe. Se le preguntará si desea permitir la instalación de este programa. Haga clic en el botón "Sí".
![image](tool_pgpwin7.png)

Se abrirá una ventana que le brinda una visión general de lo que se instalará. Haga clic en el botón "Siguiente".
![image](tool_pgpwin8.png)

Se abrirá una ventana con el acuerdo de licencia. Haga clic en el botón "Siguiente".
![image](tool_pgpwin9.png)

El paquete GPG4Win Vanilla no tiene componentes para seleccionar, entonces haga clic en el botón "Siguiente" otra vez. Para el paquete GPG4Win-Light, desmarque todos los componentes opcionales para instalar solo GnuPG.
![image](tool_pgpwin10.png)

Siguiente, tendrá la posibilidad de elegir dónde está instalado GPG. No cambie la configuración predeterminada. Haga clic en el botón "Siguiente".
![image](tool_pgpwin11.png)

Las siguientes dos ventanas tendrán algunas opciones de instalación. Haga clic en el botón "Siguiente" y luego haga clic en el botón "Instalar":
![Image](herramienta_pgpwin12.png)![Imagen](herramienta_pgpwin13.png)

Verá una ventana con un progreso bar: cuando termine, dirá "Instalación completa." Haga clic nuevamente en el botón "Siguiente".
![image](tool_pgpwin14.png)

Finalmente, se encuentra en el último paso de instalación. Quite la marca de verificación junto a "Mostrar el archivo README" y haga clic en el botón "Finish".
![image](tool_pgpwin15.png)

Eso es todo. Ahora pasemos a la instalación de Mozilla Thunderbird.

### 3.2 Instalación de Mozilla Thunderbird

De forma similar a GPG4Win, instale Mozilla Thunderbird haciendo doble clic en el archivo Thunderbird Setup 24.6.0.exe. Como de costumbre, se le preguntará si desea ejecutar este archivo. Haga clic en el botón "Ejecutar".
![image](tool_pgpwin16.png)

Se le preguntará si desea permitir que Mozilla Thunderbird realice un cambio en su computadora mediante la instalación de software. Haga clic en el botón "Sí".
![image](tool_pgpwin17.png)

Verá la ventana de configuración de Mozilla Thunderbird. Haga clic en el botón "Siguiente".
![image](tool_pgpwin18.png)

Siguiente, podrá elegir entre una configuración estándar y una configuración personalizada. Mantenga la selección de configuración estándar y haga clic en el botón "Siguiente".
![image](tool_pgpwin18.png)

Se le dará un resumen de dónde se instalarán los archivos de Mozilla Thunderbird. Haga clic en el botón "Instalar".
![image](tool_pgpwin19.png)

Cuando se complete el proceso de instalación, verá una ventana final que le permite iniciar Mozilla Thunderbird. Haga clic en el botón "Finish".
![image](tool_pgpwin20.png)

### 3.3. Instalación de Enigmail

**Paso 1. Preparación**

Cuando Mozilla Thunderbird se inicie por primera vez, verá esta pequeña ventana de confirmación preguntándole sobre algunas configuraciones predeterminadas. Recomendamos hacer clic en el botón "Establecer como predeterminado".
![image](tool_pgpwin21.png)

Siguiente, se le preguntará si desea una nueva dirección de correo electrónico. Haga clic en el botón "Omitir esto y usar mi correo electrónico existente". Ahora configurará Mozilla Thunderbird para enviar y recibir correos electrónicos. Si solo está acostumbrado a leer y enviar correos electrónicos a través de gmail.com, outlook.com o yahoo.com, Mozilla Thunderbird será una experiencia nueva, pero en general no es tan diferente.
![image](tool_pgpwin22.png)

**Paso 2. Agregar una cuenta de correo a Mozilla Thunderbird**

Se abrirá una nueva ventana.
![image](tool_pgpwin23.png)

Ingrese su nombre, dirección de correo electrónico, y la contraseña de tu cuenta de correo electrónico Mozilla no tiene acceso a su contraseña ni a su cuenta de correo electrónico. Haga clic en el botón "Continuar".
![image](tool_pgpwin24.png)

En muchos casos, Mozilla Thunderbird detectará automáticamente las configuraciones necesarias. En algunos casos, Mozilla Thunderbird no tiene información completa y deberá ingresarla usted mismo. A continuación, se incluye un ejemplo de las instrucciones que Google proporciona para Gmail:

Servidor de correo entrante (IMAP): requiere SSL
- imap.gmail.com
- Puerto: 993
- Requiere SSL: Sí

Correo saliente (SMTP) Servidor: requiere TLS
- smtp.gmail.com
- Puerto: 465 o 587
- Requiere SSL: Sí
- Requiere autenticación: Sí
- Use la misma configuración que el servidor de correo entrante

**Nombre completo o nombre para mostrar:** su nombre o seudónimo  
**Nombre de la cuenta o nombre de usuario:** su dirección completa de Gmail (username@gmail.com). Usuarios de Google Apps, ingresen username@your_domain.com  
**Dirección de correo electrónico:** su dirección completa de Gmail (username@gmail.com) Usuarios de Google Apps, ingresen username@your_domain.com  
**Contraseña:** su contraseña de Gmail

**Si usa la autenticación de dos factores con Google (y dependiendo de su modelo de amenaza, probablemente debería hacerlo) no puede usar su contraseña estándar de Gmail con Thunderbird. En su lugar, deberá crear una nueva contraseña específica de la aplicación para que Thunderbird acceda a su cuenta de Gmail. Consulte [Guía propia de Google](https://support.google.com/mail/answer/1173270?hl=en) para hacer esto.**

Cuando toda la información se ingrese correctamente, haga clic en "Hecho" "button.
![image](tool_pgpwin25.png)

Mozilla Thunderbird comenzará a descargar copias de su correo electrónico a su computadora. Intenta enviar un correo electrónico de prueba a tus amigos.

**Paso 3. Instalar Enigmail**

Enigmail se instala de forma diferente a Mozilla Thunderbird y GPG4Win. Como se mencionó anteriormente, Enigmail es un complemento para Mozilla Thunderbird. Haga clic en el "Botón de menú," también llamado botón Hamburger, y seleccione "Agregar Ons."
![image](tool_pgpwin26.png)

Se lo llevará a la pestaña del Administrador de Complementos .
![image](tool_pgpwin27.png)

Haga clic en el engranaje para abrir un pequeño menú y seleccione "Instalar add-on desde el archivo" que abrirá una ventana de selección de archivos.
![ image](tool_pgpwin28.png)

Es muy probable que la ventana de selección de archivos se abra en la carpeta Descargas. Si no lo hace, vaya a la carpeta de Descargas (donde se guardó Enigmail) haga clic en enigmail-1.7-tb + sm.xpi y luego haga clic en el botón "Abrir".
![image](tool_pgpwin29.png)

Ahora verá una pequeña ventana que le pedirá que confirme si desea instalar Enigmail. Haga clic en el botón "Instalar ahora".
![image](tool_pgpwin30.png)

Después de instalar el complemento Enigmail, Mozilla Thunderbird le pedirá que reinicie el navegador para activar Enigmail. Haga clic en el botón "Reiniciar ahora" y Mozilla Thunderbird se reiniciará.
![image](tool_pgpwin31.png)

Cuando se reinicie Mozilla Thunderbird, se abrirá una ventana adicional que iniciará el proceso de configuración de Enigmail Añadir. Mantenga el botón "Sí, me gustaría que el asistente me haga funcionar" y haga clic en el botón "Siguiente".
![Image](tool_pgpwin32.png)

Enigmail le proporciona tres opciones para manejo de correo. La opción predeterminada es cifrar los correos electrónicos si tiene la "clave pública" de otra persona, Enigmail cifrará el correo electrónico que envía pero dejará los correos electrónicos sin cifrar si todavía no tiene la clave pública del destinatario. También tiene la opción de encriptar correos electrónicos todo el tiempo a todos con las llaves PGP, lo que significa que tendrá que encontrar las claves públicas para las personas para las que aún no las tiene, o desactivar por completo el cifrado automático y solo usar PGP cuando se lo indique.
![image](tool_pgpwin33.png)

No sabemos cuál es la opción adecuada para usted, pero creemos que la opción "Convenient auto encryption" es una buena opción. Si tiene dudas, elija "No cifre mis mensajes de forma predeterminada." Haga clic en el botón "Siguiente".

Ahora tiene la opción de firmar digitalmente todos los correos electrónicos salientes. Firmar su correo electrónico con PGP le permite al destinatario verificar que haya enviado el mensaje y que no haya alterado el contenido del mensaje. Haga clic en el botón "Firmar mis mensajes por defecto" para activar esta característica. La desventaja de hacer esto, sin embargo, es que también puede marcar a cualquiera a quien le envíe correo que use PGP. [En algunas partes del mundo](www.cryptolaw.org/) (incluidos China, Irán, Bielorrusia y algunos estados del Medio Oriente) el uso de encriptación sin licencia, incluso para uso personal, es ilegal, por lo que puede tener muy buenas razones para que los demás no sepan que usa PGP.

Haga clic en el botón "Siguiente".
![image](tool_pgpwin34.png)

Ahora verá una opción para que Enigmail realice algunos cambios en el configuración de Mozilla Thunderbird.
![image](tool_pgpwin35.png)

Si hace clic en el botón Detalles, puede revisar cuáles son esos cambios.
![image](tool_pgpwin36.png)

Las siguientes opciones puede ser desmarcado (reactivado), para una transición más fluida, si usa PGP / Mime de manera predeterminada (lo configuraremos más adelante):

- Deshabilitar texto circulado
- Ver el cuerpo del mensaje como texto sin formato
- No redacte mensajes HTML.

La opción final evita posibles problemas en el cifrado y descifrado de su correo electrónico. Tenga en cuenta que al seleccionar esta casilla se eliminará la posibilidad de enviar texto en negrita, subrayado o coloreado. Después de revisar los cambios, haga clic en el botón "Aceptar."

La pequeña ventana se cerrará. Haga clic en el botón "Siguiente".

Ahora comenzará a crear su clave privada y clave pública.

### 4 Creando una clave pública y una clave privada

Instalación y configuración de Enigmail add- encendido está completo. Ahora tendrá la opción de crear su par de claves pública y privada. Esto supone que no ha creado una clave privada antes.

Haga clic en el botón "Siguiente".
![Image](tool_pgpwin37.png)

A menos que haya configurado más de una cuenta de correo electrónico, Enigmail elija la cuenta de correo electrónico que ya ha configurado. Lo primero que tendrá que hacer es crear una contraseña segura para su clave privada. Consulte la **[lección de contraseñas](umbrella://lesson/passwords)** para obtener más información sobre cómo hacer esto.

Asegúrese de haber anotado esta frase de contraseña en papel hasta que la haya memorizado. Guárdelo en algún lugar donde pueda saber si se lo tomaron o vieron (como su billetera o cartera). Solo asegúrese de no dejar este documento por ahí.

Haga clic en el botón "Siguiente".

Enigmail mostrará información sobre su clave privada y sobre la configuración. Recomendamos crear claves de longitud de 4096 bits. Haga clic en el botón "Siguiente".
![image](tool_pgpwin38.png)

**Su clave caducará en un momento determinado; cuando eso sucede, otras personas dejarán de usarlo por completo para recibir correos electrónicos nuevos, aunque es posible que no reciba ninguna advertencia o explicación sobre por qué. Por lo tanto, es posible que desee marcar su calendario y prestar atención a este problema aproximadamente un mes antes de la fecha de vencimiento.**

Es posible prolongar el período de vigencia de una clave existente dándole una nueva fecha de vencimiento posterior o es posible reemplazarlo con una nueva clave creando uno nuevo desde cero. Ambos procesos pueden requerir el contacto con personas que le envían correos electrónicos y se aseguran de que obtengan la clave actualizada; el software actual no es muy bueno para automatizar esto. Así que haz un recordatorio por ti mismo; si no crees que puedas gestionarlo, puedes considerar configurar la clave para que nunca caduque, aunque en ese caso otras personas podrían tratar de usarlo cuando te contacten en el futuro, incluso si ya no lo haces. tiene la clave privada o ya no usa PGP.

Enigmail generará la clave y, cuando se complete, se abrirá una pequeña ventana que le pedirá que genere un certificado de revocación. Es importante tener este certificado de revocación, ya que le permite hacer que la clave privada y la clave pública no sean válidas. Es importante tener en cuenta que simplemente eliminar la clave privada no invalida la clave pública y puede hacer que las personas le envíen mensajes encriptados que no puede descifrar.

Haga clic en el botón "Generar certificado".
![image](tool_pgpwin39.png)

Se abrirá una ventana para proporcionarle un lugar donde guardar el certificado de revocación. Mientras puede guardar el archivo en su computadora, le recomendamos que guarde el archivo en una unidad USB que está utilizando para nada más y que guarde la unidad en un lugar seguro. También recomendamos eliminar el certificado de revocación de la computadora con las claves, solo para evitar la revocación involuntaria.

Incluso mejor, guarde este archivo en un disco cifrado diferente. Elija la ubicación donde está guardando este archivo y haga clic en el botón "Guardar".
![image](tool_pgpwin40.png)

Ahora, Enigmail le dará más información sobre cómo guardar nuevamente el archivo de certificado de revocación. Haga clic en el botón "Aceptar".
![image](tool_pgpwin41.png)

Finalmente, ha terminado de generar la clave privada y la clave pública. Haga clic en el botón "Finish".
![image](tool_pgpwin42.png)

### 5 Pasos opcionales

### 5.1 Mostrar long-key IDs

Los siguientes pasos son completamente opcional pero pueden ser útiles al usar OpenPGP y Enigmail. En resumen, el ID de clave es una pequeña parte de la huella digital. Cuando se trata de verificar que una clave pública pertenece a una persona en particular, la huella dactilar es la mejor manera. Cambiar la pantalla predeterminada facilita la lectura de las huellas dactilares de los certificados que conoce. Haga clic en el botón de configuración, luego en la opción Enigmail y luego en Gestión de claves.
![image](tool_pgpwin43.png)

Se abrirá una ventana que muestra dos columnas: Nombre e ID de clave.
![image](tool_pgpwin43.png)

En el extremo derecho hay un pequeño botón. Haga clic en ese botón para configurar las columnas. Desmarque la opción ID de clave y haga clic en la opción Huella digital.
![image](tool_pgpwin44.png)

Ahora las columnas se verán así:
![image](tool_pgpwin45.png)

Ahora usted está configurado para enviar y recibir correo electrónico regular y encriptado. A continuación, realizará los pasos para encontrar realmente a las personas con las que intercambiar correo cifrado.

### 5.2 Utilizar PGP / MIME

Hay un último paso de configuración opcional para habilitar PGP / MIME, lo que hace que el envío se encripte y los archivos adjuntos firmados son más fáciles.

Puede encontrar esta configuración haciendo clic en el botón de menú, al pasar el mouse sobre Opciones y luego hacer clic en Configuración de la cuenta. Se abrirá la ventana Configuración de la cuenta.
![Imagen](herramienta_pgpwin46.png)

Cuando se abra la ventana Configuración de la cuenta, haga clic en la pestaña Seguridad OpenPGP y luego haga clic en la casilla de verificación junto a Usar PGP / MIME. Luego haz clic en el botón Aceptar. Ahora Enigmail usará PGP / MIME de forma predeterminada.
![image](tool_pgpwin47.png)

**El uso de PGP no encripta completamente su correo electrónico para que el remitente y la información recibida estén encriptados. Encriptar la información del remitente y del receptor rompería el correo electrónico. El uso de Thunderbird con el complemento Enigmail le brinda una forma fácil de encriptar y descifrar el contenido de su correo electrónico.**

### 6.1 Informar a otras personas que está usando PGP

Ahora que tenga PGP, usted desea que los demás sepan que lo está usando para que también puedan enviarle mensajes cifrados con PGP.

Examinemos tres maneras diferentes para que las personas sepan que está utilizando PGP.

**a) Permita que las personas sepa que está utilizando PGP con un correo electrónico**

Puede enviar fácilmente una clave pública a otra persona enviándole una copia como archivo adjunto.

Haga clic en el botón "Escribir" en Mozilla Thunderbird.
![image](tool_pgpwin48.png)

Resuma en una dirección y un asunto, tal vez algo como "mi clave pública," haz clic en el menú Enigmail y selecciona la opción "Adjuntar mi clave pública".
![image](tool_pgpwin49.png)

Puede enviar el correo electrónico y el destinatario podrá descargar y usar la clave pública que envió.

Si se utiliza este método, es una buena idea que el destinatario verifique la huella dactilar de tu llave pública int sobre alguna otra forma de comunicación, en caso de que el correo electrónico ya esté siendo interceptado y manipulado.

**b) Haga saber a la gente que está usando PGP en su sitio web**

Además de informar a la gente por correo electrónico , puede publicar su clave pública en su sitio web. La forma más fácil es subir el archivo y vincularlo. Esta guía no explicará cómo hacer esas cosas, pero debe saber cómo exportar el certificado como un archivo para usar en el futuro.

Haga clic en el botón de configuración, luego en la opción Enigmail y luego en Administración de claves.

Resalte el certificado en negrita, luego haga clic con el botón derecho para abrir el menú y seleccione Exportar claves al archivo.
![image](tool_pgpwin50.png)

Una ventana pequeña aparecerá con tres botones. Haga clic en el botón "Exportar solo claves públicas".
![image](tooL_pgpwin51.png)

Asegúrese de no hacer clic en el botón "Exportar claves secretas" porque exportar la clave secreta podría permitir que otros para suplantarlo si pueden adivinar su contraseña.

Ahora se abrirá una ventana para que pueda guardar el archivo. Para que sea más fácil encontrarlo en el futuro, guarde el archivo en la carpeta Documentos.
![image](tool_pgpwin52.png)

Ahora puede usar este archivo como lo desee.

**c) Carga en un servidor de claves**

Los servidores de servidores hacen que sea más fácil buscar y descargar claves públicas. La mayoría de los servidores de claves modernos se sincronizan, lo que significa que una clave pública cargada en un servidor llegará eventualmente a todos los servidores.

Aunque subir tu clave pública a un servidor de claves podría ser una manera conveniente de hacerles saber que tienes un certificado público de PGP, debe saber que debido a la naturaleza de cómo funcionan los servidores de claves, no hay forma de eliminar las claves públicas una vez que se cargan, solo puede marcarlas como revocadas.

**Antes de cargar su clave pública a un servidor de claves, es Es bueno tomarse un momento para considerar si desea que todo el mundo sepa que tiene una clave pública sin la capacidad de eliminar esta información en un momento posterior.**

Si elige subir su clave pública a los servidores de claves, volverá a la ventana Administración de claves Enigmail.

Haga clic en el elemento del menú Keyserver y seleccione la opción Cargar claves públicas.
![image](tool_pgpwin53.png)

### 6.2 Encontrar a otras personas que estén utilizando PGP

**a) Obteniendo una clave pública por correo electrónico**

Es posible que obtenga una clave pública que se envía t o usted como adjunto de correo electrónico.
![image](tool_pgpwin54.png)

Haga doble clic en el nuevo mensaje y se abrirá una nueva pestaña. Observe el archivo adjunto en la parte inferior de la ventana. Haga clic derecho en el archivo adjunto y seleccione "Importar clave OpenPGP." Se abrirá una pequeña ventana que le dará los resultados de la importación. Haga clic en el botón Aceptar.
![image](tool_pgpwin55.png)

Si vuelve a abrir la ventana de administración de claves Enigmail, puede verificar el resultado. Su clave PGP está en negrita porque tiene tanto la clave privada como la pública. La clave pública que acaba de importar no está en negrita porque no contiene la clave privada.
![image](tool_pgpwin56.png)

**b) Obtener una clave pública como un archivo**

Es posible que obtenga una clave pública descargándola de un sitio web o que alguien la haya enviado a través del software de chat. En un caso como este, supondrá que ha descargado el archivo en la carpeta Descargas.

Abra el Enigmail Key Manager y haga clic en el menú "Archivo". Seleccione "Importar claves del archivo."
![image](tool_pgpwin57.png)

La clave pública puede tener terminaciones de nombre de archivo muy diferentes, como .asc, .pgp o .gpg. Seleccione el archivo y haga clic en el botón "Abrir".
![image](tool_pgpwin58.png)

Se abrirá una pequeña ventana que le mostrará los resultados de la importación. Haga clic en el botón "Aceptar".
![image](tool_pgpwin59.png)

**c) Obtener una clave pública de un servidor de claves**

Seriedores de servidores puede ser una forma muy útil de obtener claves públicas Intenta buscar una clave pública. Abra el administrador de claves y luego haga clic en el menú "Keyserver" y seleccione "Search for Keys."
![image](tool_pgpwin60.png)

Una ventana pequeña aparecerá con un campo de búsqueda. Puede buscar por una dirección de correo electrónico completa, una dirección de correo electrónico parcial o un nombre. En este caso, buscará certificados que contengan "eff.org."
![image](tool_pgpwin61.png)

Una ventana más grande aparecerá con muchas opciones. Si se desplaza hacia abajo notará que algunos certificados están en cursiva y atenuados. Estos son certificados que han sido revocados o caducados por su cuenta.
![image](tool_pgpwin62.png)

Llevamos las claves públicas de Danny O'Brien por ejemplo, él tiene un certificado caducado o revocado y uno certificado válido Seleccione el certificado válido haciendo clic en el cuadro de la izquierda y luego presione el botón OK.
![image](tool_pgpwin63.png)

En algunos casos, una persona puede tener más de un certificado, y todos son válidos. Tenga en cuenta que es posible que cualquier persona cargue un certificado público para cualquier otra persona, y que una de estas claves puede no pertenecer a la persona propietaria de la dirección de correo electrónico asociada. En este caso, la verificación de la huella dactilar es extremadamente importante.

Aparecerá una pequeña ventana de notificación que le informará si tuvo éxito:
![image](tool_pgpwin64.png)

El Enigmail Key Manager ahora le mostrará los certificados agregados:
![image](tool_pgpwin65.png)

### 7.1 Envío de correo cifrado PGP

Ahora enviará su primer correo cifrado a un destinatario. En la ventana principal de Mozilla Thunderbird, haga clic en el botón "Escribir". Se abrirá una nueva ventana.
![image](tool_pgpwin66.png)

Escriba su mensaje e ingrese un destinatario. Para esta prueba, seleccione un destinatario cuya clave pública ya tiene. Enigmail detectará esto y encriptará automáticamente el correo electrónico.
![image](tool_pgpwin67.png)

Note que la línea de asunto no estará encriptada, así que elige algo inocuo, como "hello."

Cuando hace clic en el botón "Enviar", se le dará una ventana para ingresar la contraseña de su clave PGP. ¡Recuerde que esto es diferente de su contraseña de correo electrónico!

Ingrese su contraseña y luego haga clic en el botón "OK" y su correo electrónico será encriptado y enviado.
![image](tool_pgpwin68.png)

El cuerpo de el correo electrónico fue encriptado y transformado. Por ejemplo, este texto:
![image](tool_pgpwin69.png)

Se transformará en:
![image](tool_pgpwin70.png)

### 7.2 Recepción de correo cifrado PGP

Pasemos por lo que sucede cuando recibe correos electrónicos encriptados. Tenga en cuenta que Mozilla Thunderbird le informa que tiene correo nuevo. Haga clic en el mensaje.
![image](too.png; _pgpwin71)

Se abre una pequeña ventana que le solicita la contraseña de la clave PGP. Recuerde: no ingrese su contraseña de correo electrónico. Haga clic en el botón "Aceptar".
![image](tool_pgpwin72.png)

Now el mensaje aparecerá descifrado
![image](tool_pgpwin73.png)

### 8 Revocando la clave PGP

**a) Revocar su clave PGP a través de la interfaz Enigmail**

Las claves PGP generadas por Enigmail expiran automáticamente después de cinco años. Por lo tanto, si pierde todos sus archivos, puede esperar que la gente sepa pedirle otra clave una vez que la clave haya expirado.

Podría tener una buena razón para desactivar la clave PGP antes de que caduque. Quizás desee generar una clave PGP nueva y más sólida. La forma más fácil de revocar su propia clave PGP en Enigmail es a través del Enigmail Key Manager.
![image](tool_pgpwin74.png)

Haga clic con el botón derecho en su clave PGP (está en negrita) y seleccione la "Revoque la opción" clave
![image](tool_pgpwin75.png)

Aparecerá una ventana que le informará qué sucede y le pedirá confirmación. Haga clic en el botón "Revocar clave".
![image](tool_pgpwin76.png)

Se abre la ventana de contraseña, ingrese su contraseña para la clave PGP y haga clic en el botón "OK".
![ image](tool_pgpwin77.png)

Ahora se abrirá una nueva ventana que le informa que tuvo éxito. Haga clic en el botón "OK".
![image](tool_pgpwin78.png)

Cuando regrese a la ventana Enigmail Key Management notará un cambio en su clave PGP. Ahora está en gris y en cursiva.
![image](tool_pgpwin79.png)

**b) Revocación de una clave PGP con un certificado de revocación**

Como se mencionó anteriormente, las claves PGP generadas por Enigmail caduca automáticamente después de cinco años. Entonces, si pierde todos sus archivos, puede estar seguro de que la gente sabrá pedirle otra clave una vez que la llave haya expirado.

Como mencionamos anteriormente, es posible que tenga una buena razón para desactivar la clave PGP antes de que caduque.

De forma similar, otros podrían tener buenas razones para revocar una clave existente.

Es posible que recibas certificados de revocación de amigos como un aviso de que quieren revocar su clave.

En la sección anterior, habrás notado que Enigmail genera e importa un certificado de revocación internamente cuando utiliza Enigmail Key Manager para revocar una clave. Como ya tiene un certificado de revocación, usará el que generó anteriormente para revocar su propia clave.

Comience con Enigmail Key Manager y haga clic en el menú "Archivo" y seleccione "Importar claves del archivo."
![image](tool_pgpwin80.png)

Se abrirá una ventana para que pueda seleccionar el certificado de revocación. Haga clic en el archivo y haga clic en el botón "Abrir".
![image](tool_pgpwin81.png)

Recibirá una notificación de que el certificado se importó con éxito y que una clave fue revocada. Haga clic en el botón "OK".
![image](tool_pgpwin82.png)

Una vez que haga clic en el botón "OK ", volverá al Enigmail Key Manager y verá el certificado. revocado en gris y en cursiva.
![image](tool_pgpwin83.png)

Si la clave que revocó es la suya, y anteriormente ha cargado su clave pública en los servidores de claves, querrá volver a cargar el archivo. ahora, la clave revocada para los servidores de claves, para que otros vean que ya no la usan más.

Ahora que tiene todas las herramientas adecuadas, intente enviar su propio correo electrónico cifrado con PGP.
