[Title]: # ()
[Difficulty]: # (Principiante)
[Order]: # (0)

# PGP FOR LINUX TOOL GUIDE 

## PGP para Linux Tool Guide
Email encriptado para Linux 

**Lección para leer:**

- [Correo electrónico](umbrella://lesson/email) **
**Requisitos de la computadora:** Una conexión a Internet, una computadora con Linux, una cuenta de correo electrónico
**Versión utilizada en esta guía:**
- Linux: Debian 7.0 ("Wheezy")
- Mozilla Thunderbird 24.8.1
- Enigmail 1.6
- GPG4Win 1.4.18
**Licencia:** Software Libre; combinación de licencias de Software Libre
**Nivel:** Experto
**Otra lectura:** [https://www.gnupg.org/documentation/guides.html](https://www.gnupg.org/documentation/guides.html)
**Tiempo requerido:** 30-60 minutos

**El uso de PGP le dará:**
- La capacidad de proteger sus comunicaciones de correo electrónico para que nadie las lea. sus destinatarios previstos.
- La capacidad de demostrar que un correo electrónico provino de una persona en particular, en lugar de ser un mensaje falso enviado por otro remitente (de lo contrario, es muy fácil que se fabrique el correo electrónico). Ambas son defensas importantes si está siendo objeto de vigilancia o desinformación.

### 1.0 Antes de comenzar

Para usar Pretty Good Privacy (PGP), deberá instalar algún software adicional que lo trabaja con tu programa de correo electrónico actual. También necesitarás crear una clave privada, que mantendrás en privado. La clave privada es lo que usará para descifrar los correos electrónicos que se le envían, y para firmar digitalmente correos electrónicos que envíe para mostrar que realmente provienen de usted. Finalmente, aprenderá cómo distribuir su clave pública, una pequeña porción de información que otros necesitarán saber antes de poder enviarle correos encriptados, y que pueden usar para verificar los correos electrónicos que envía.

Esta guía mostrará cómo usar PGP con un sistema operativo estilo Linux usando Mozilla Thunderbird, un popular cliente de correo electrónico gráfico de código abierto.

No puede usar PGP directamente con un servicio de correo electrónico web como Gmail, Hotmail, Yahoo! Correo o Outlook Live. Aún puede usar su dirección de correo web; solo tendrá que configurarlo con el programa Thunderbird en su computadora.

** Tenga en cuenta que ambos extremos de la conversación por correo electrónico deben estar usando un software compatible con PGP para que funcione. **

La gente lo hará Normalmente, use esto solo en sus dispositivos personales, no en dispositivos compartidos. Afortunadamente, PGP está disponible para la mayoría de las computadoras de escritorio y dispositivos móviles, y puede dirigirlas a estas guías para ayudarlas a configurar su propia versión.

### 2.0 Instalar Thunderbird, GnuPG y Enigmail

PGP es una estándar abierto, lo que significa que más de una pieza de software puede usarlo. El software que vamos a usar para PGP se llama GnuPG. También agregaremos un complemento a Thunderbird llamado Enigmail, que le permite usar GnuPGP desde Thunderbird. Las siguientes instrucciones requieren cierta comodidad con la línea de comandos.

Si está usando una distribución basada en Red Hat como Red Hat o Fedora Core, abra una terminal y ejecute estos comandos:

_sudo yum install gnupg thunderbird thunderbird-enigmail_

Si está utilizando una distribución basada en Ubuntu como Ubuntu o Linux Mint, abra un terminal y escriba estos comandos para asegurarse de tener el software correcto instalado:

_sudo apt-get install gnupg thunderbird enigmail_

Si está usando la distribución de Debian, encontrará que Thunderbird se llama "Icedove." Al igual que Debian en general, esto es por razones completamente raras pero algo oscuras. Aparte del nombre, es exactamente el mismo programa: no volveremos a mencionar a Icedove, pero puede reemplazar "Thunderbird" con Icedove en el resto de esta guía, y todo debería funcionar.

Utilice este comando en la Terminal para instalarlo:

_sudo apt-get install gnupg icedove enigmail_

### 2.1 Configurando Thunderbird

Ahora que ha instalado Thunderbird, ábralo como lo haría con otra aplicación en su máquina ( puede seleccionarlo de una lista de aplicaciones en un menú, o escribir su nombre en una búsqueda de aplicación). Verá que aparece el asistente de la primera ejecución.
![image](tool_pgplin1.png)

Para configurar su dirección de correo electrónico existente, haga clic en "Omitir esto y use mi correo electrónico existente," y luego ingrese su nombre, dirección de correo electrónico y la contraseña de su cuenta de correo electrónico.
![image](tool_pgplin2.png)

Si usa un popular servicio gratuito de correo electrónico como Gmail, Thunderbird debería poder detectar automáticamente su configuración de correo electrónico al hacer clic en "Continuar. "

** Si usa la autenticación de dos factores con Google (y dependiendo de su modelo de amenaza, probablemente debería hacerlo) no puede usar su contraseña de Gmail estándar con Thunderbird. En su lugar, deberá crear una nueva contraseña específica de la aplicación para que Thunderbird acceda a su cuenta de Gmail. Consulte [Guía propia de Google](https://support.google.com/mail/answer/1173270?hl=es) para hacer esto. **
![image](tool_pgplin3.png)

Si no lo hace 't, es posible que deba configurar manualmente sus configuraciones IMAP y SMTP. Si no sabe cómo hacerlo, hable con su proveedor de correo electrónico, o pregúntele a alguien técnico que esté familiarizado con su proveedor de correo electrónico (por lo tanto, una persona de TI en el trabajo, o un amigo técnico que utiliza el mismo ISP que usted; no necesita saber cómo usar PGP, pero puede preguntarles "¿Conocen las configuraciones de IMAP y SMTP para mi dirección de correo electrónico?").

### 2.2 Configurando Enigmail

Enigmail es un complemento para Thunderbird que encripta y descifra los correos electrónicos codificados con PGP, y hace que el manejo de las claves privadas y públicas sea un poco más fácil. Si tiene la última versión de Enigmail, se le debe presentar el Asistente de configuración de Enigmail.
![image](tool_pgplin4.png)

Si no lo ve, puede usar esta opción del menú de Thunderbird para hacer que aparezca Haga clic en las tres líneas horizontales (el "menú de hamburguesas ") a la derecha de la ventana de Thunderbird.
![image](tool_pgplin5.png)

Esta es la primera opción que Enigmail le ofrece: tres opciones para el manejo cuándo encriptar su correo.
![image](tool_pgplin6.png)

La opción predeterminada es encriptar los correos electrónicos si tiene la "clave pública" de otra persona, Enigmail encriptará el correo electrónico que envíe pero se irá correos electrónicos no cifrados si aún no tiene la clave pública del destinatario. También tiene la opción de encriptar correos electrónicos todo el tiempo a todos con las llaves PGP, lo que significa que tendrá que encontrar las claves públicas para las personas para las que aún no las tiene, o desactivar completamente el cifrado automático y solo usar PGP when directed.

No sabemos cuál es la opción adecuada para usted, pero creemos que la opción "Convenient auto encryption" es una buena opción. Si tiene dudas, elija "No encripte mis mensajes por defecto. "

Haga clic en el botón "Siguiente".
![image](tool_pgplin6.png)

Ahora tiene una opción para firmar digitalmente todos los correos salientes. Firmar su correo electrónico con PGP le permite al destinatario verificar que haya enviado el mensaje y que no haya alterado el contenido del mensaje. Haga clic en el botón "Firmar mis mensajes por defecto" para activar esta característica.

La desventaja de hacer esto, sin embargo, es que también puede marcar a cualquiera a quien le envíe correo que use PGP. [En algunas partes del mundo](www.cryptolaw.org/) (incluidos China, Irán, Bielorrusia y algunos estados del Medio Oriente) el uso de encriptación sin licencia, incluso para uso personal, es ilegal, por lo que puede tener muy buenas razones para que los demás no sepan que usa PGP.

Haga clic en el botón "Siguiente".

Ahora verá una opción para que Enigmail realice algunos cambios en la configuración de Mozilla Thunderbird.
![imagen](tool_pgplin7.png)

Si hace clic en el botón Detalles puede revisar cuáles son esos cambios.

Las siguientes opciones se pueden desmarcar (volver a habilitar), para una transición más fluida, si usa PGP / Mime de forma predeterminada ( lo configuraremos más adelante):
- Deshabilitar el texto circulado
- Ver el cuerpo del mensaje como texto sin formato
- No redactar mensajes HTML

La opción final previene posibles problemas en el cifrado y descifrado de su correo electrónico. Tenga en cuenta que al seleccionar esta casilla se eliminará la posibilidad de enviar texto en negrita, subrayado o coloreado. Después de revisar los cambios, haga clic en el botón "Aceptar. "

Ahora comenzará a crear su clave privada y clave pública.

### 2.3 Creación de una clave pública y una clave privada

Instalación y configuración del complemento Enigmail está completo. Ahora tendrá la opción de crear su par de claves pública y privada. Esto supone que no ha creado una clave privada antes.
![image](tool_pgplin8.png)

Haga clic en el botón "Siguiente".

A menos que haya configurado más de una cuenta de correo electrónico, Enigmail elija la cuenta de correo electrónico que ya ha configurado. Lo primero que tendrá que hacer es crear una contraseña segura para su clave privada. Consulte la ** [lección de contraseñas](paraguas: // lección / contraseñas) ** para obtener más información sobre cómo hacer esto.

Enigmail mostrará cierta información sobre su clave privada, así como la configuración. Recomendamos crear claves de longitud de 4096 bits. Haga clic en el botón "Siguiente".
![image](tool_pgplin9.png)

** Su clave caducará en un momento determinado; cuando eso sucede, otras personas dejarán de usarlo por completo para recibir correos electrónicos nuevos, aunque es posible que no reciba ninguna advertencia o explicación sobre por qué. Por lo tanto, es posible que desee marcar su calendario y prestar atención a este problema aproximadamente un mes antes de la fecha de vencimiento. **

Es posible prolongar el período de vigencia de una clave existente dándole una nueva fecha de vencimiento posterior o es posible reemplazarlo con una nueva clave creando uno nuevo desde cero. Ambos procesos pueden requerir el contacto con personas que le envían correos electrónicos y se aseguran de que obtengan la clave actualizada; el software actual no es muy bueno para automatizar esto. Así que haz un recordatorio por ti mismo; si no crees que puedas gestionarlo, puedes considerar configurar la clave para que nunca caduque, aunque en ese caso otras personas podrían tratar de usarlo cuando te contacten en el futuro, incluso si ya no lo haces. tiene la clave privada o ya no usa PGP.

Enigmail generará la clave y, cuando se complete, se abrirá una pequeña ventana que le pedirá que genere un certificado de revocación. Es importante tener este certificado de revocación, ya que le permite hacer que la clave privada y la clave pública no sean válidas. Es importante tener en cuenta que la simple eliminación de la clave privada no invalida la clave pública y puede hacer que las personas le envíen un correo cifrado que no puede descifrar.
![image](tool_pgplin10.png)

Haga clic en \ Botón "Generar certificado".

Se abrirá una ventana para proporcionarle un lugar donde guardar el certificado de revocación. Mientras puede guardar el archivo en su computadora, le recomendamos que guarde el archivo en una unidad USB que está utilizando para nada más y que guarde la unidad en un lugar seguro. También recomendamos eliminar el certificado de revocación de la computadora con las claves, solo para evitar la revocación involuntaria.

Incluso mejor, guarde este archivo en un disco cifrado diferente. Elija la ubicación donde está guardando este archivo y haga clic en el botón "Guardar".

Ahora, Enigmail le dará más información sobre cómo guardar el archivo de certificado de revocación de nuevo. Haga clic en el botón "Aceptar".

Finalmente, ha terminado de generar la clave privada y la clave pública. Haga clic en el botón "Finalizar".

### 2.4 Pasos opcionales

### 2.4.1 Mostrar ID de clave larga

Los próximos pasos son completamente opcionales pero pueden ser útiles cuando se usa OpenPGP y Enigmail. En resumen, el ID de clave es una pequeña parte de la huella digital. Cuando se trata de verificar que una clave pública pertenece a una persona en particular, la huella dactilar es la mejor manera. Cambiar la pantalla predeterminada facilita la lectura de las huellas dactilares de los certificados que conoce. Haga clic en el botón de configuración, luego en la opción Enigmail y luego en Gestión de claves.
![image](tool_pgplin11.png)

Se abrirá una ventana con dos columnas: Nombre e ID de clave.
![image](tool_pgplin12. png)

En el extremo derecho hay un pequeño botón. Haga clic en ese botón para configurar las columnas. Desmarque la opción ID de clave y haga clic en la opción Huella digital.
![imagen](herramienta_pgplin13.png)

Ahora cambie el ancho de la columna Huella digital moviendo el mouse hacia las líneas entre cada encabezado de columna (es decir, solo para a la izquierda del encabezado "ID de clave" en la parte superior de la lista de teclas) y arrastrando la línea hacia la izquierda. Sigue moviéndote hacia la izquierda hasta que puedas ver toda la identificación de clave, así:

Ahora las columnas se verán así:
![image](tool_pgplin14.png)

Ahora estás configurado para enviar y recibir correo electrónico regular y encriptado A continuación, realizará los pasos para encontrar realmente a las personas con las que intercambiar correo cifrado.

** El uso de PGP no encripta completamente su correo electrónico para que la información del remitente y el receptor esté encriptada. Encriptar la información del remitente y del receptor rompería el correo electrónico. El uso de Thunderbird con el complemento Enigmail le brinda una manera fácil de cifrar y descifrar el contenido de su correo electrónico. **

### 3.0 Informar a otras personas que está utilizando PGP

** a) Permitir que las personas sepa que está utilizando PGP con un correo electrónico **

Puede enviar su clave pública fácilmente a otra persona enviándole una copia como archivo adjunto.

Haga clic en el botón "Escribir" en Mozilla Thunderbird.

Rellenar una dirección y un asunto, tal vez algo como "mi clave pública," hacer clic en el menú Enigmail y seleccionar la opción "Adjuntar mi clave pública".
![image](tool_pgplin15.png)

Puede ahora el correo electrónico y el destinatario podrán descargar y usar la clave pública que envió.

** Si se utiliza este método, es una buena idea que el destinatario verifique la huella digital de su clave pública en alguna otra forma. de comunicación, en caso de que el correo electrónico ya sea interceptado y manipulado. **

** b) Haga saber a la gente que está utilizando PGP en su sitio web **

Además de informar a las personas por correo electrónico, puede Publica tu público clave en su sitio web. La forma más fácil es subir el archivo y vincularlo. Esta guía no explicará cómo hacer esas cosas, pero debe saber cómo exportar el certificado como un archivo para usar en el futuro.

Haga clic en el botón de configuración, luego en la opción Enigmail y luego en Administración de claves.

Haga resaltar su certificado en negrita, luego haga clic con el botón derecho para abrir el menú y seleccione Exportar claves al archivo.
![image](tool_pgplin16.png)

Una ventana pequeña aparecerá con tres botones. Haga clic en el botón "Exportar solo claves públicas".
![image](tool_pgplin17.png)


** Asegúrese de no hacer clic en el botón "Exportar claves secretas" porque está exportando el la clave secreta podría permitir que otros se hagan pasar por usted si son capaces de adivinar su contraseña. **

Ahora se abrirá una ventana para que pueda guardar el archivo. Para que sea más fácil encontrarlo en el futuro, guarde el archivo en la carpeta Documentos.

Ahora puede usar este archivo como lo desee.

** c) Cargar en un servidor de claves **

Keyservers hace que sea más fácil buscar y descargar claves públicas. La mayoría de los servidores de claves modernos se sincronizan, lo que significa que una clave pública cargada en un servidor llegará eventualmente a todos los servidores.

Aunque subir tu clave pública a un servidor de claves podría ser una manera conveniente de hacerles saber que tienes un certificado público de PGP, debe saber que debido a la naturaleza de cómo funcionan los servidores de claves, no hay forma de eliminar las claves públicas una vez que se cargan, solo puede marcarlas como revocadas.

** Antes de cargar su clave pública a un servidor de claves, es es bueno tomarse un momento para considerar si desea que todo el mundo sepa que tiene una clave pública sin la capacidad de eliminar esta información en un momento posterior. **

Si elige subir su clave pública a los servidores de claves, volverá a la ventana Administración de claves Enigmail.

Haga clic en el elemento del menú Keyserver y seleccione la opción Cargar claves públicas.
![image](tool_pgplin18.png)

### 3.1 Encontrar a otras personas que estén utilizando PGP

** a) Obteniendo una clave pública por correo electrónico **

Es posible que obtenga una clave pública que se envía t o usted como un archivo adjunto de correo electrónico.
![image](tool_pgplin19.png)

Tenga en cuenta el archivo adjunto en la parte inferior de la ventana. Haga clic derecho en el archivo adjunto y seleccione "Importar clave OpenPGP." Se abrirá una pequeña ventana que le dará los resultados de la importación. Haga clic en el botón Aceptar.

Si vuelve a abrir la ventana de administración de claves Enigmail, puede verificar el resultado. Su clave PGP está en negrita porque tiene tanto la clave privada como la pública. La clave pública que acaba de importar no está en negrita porque no contiene la clave privada.
![image](tool_pgplin20.png)

** b) Obtener una clave pública como un archivo **

Es posible que obtenga una clave pública descargándola de un sitio web o que alguien la haya enviado a través del software de chat. En un caso como este, supondrá que ha descargado el archivo en la carpeta Descargas.

Abra el Enigmail Key Manager y haga clic en el menú "Archivo". Seleccione "Importar claves del archivo. "

La clave pública puede tener terminaciones de nombre de archivo muy diferentes, como .asc, .pgp o .gpg. Seleccione el archivo y haga clic en el botón "Abrir". Se abrirá una pequeña ventana que le mostrará los resultados de la importación. Haga clic en el botón "Aceptar".

** c) Obtener una clave pública de un servidor de claves **

Serie servidores puede ser una forma muy útil de obtener claves públicas. Intenta buscar una clave pública. Abra el administrador de claves y luego haga clic en el menú "Keyserver" y seleccione "Search for Keys. "
![image](tool_pgplin21.png)

Una ventana pequeña aparecerá con un campo de búsqueda. Puede buscar por una dirección de correo electrónico completa, una dirección de correo electrónico parcial o un nombre. En este caso, buscará certificados que contengan "eff.org. "
![image](tool_pgplin22.png)

Una ventana más grande aparecerá con muchas opciones. Si se desplaza hacia abajo notará que algunos certificados están en cursiva y atenuados. Estos son certificados que han sido revocados o caducados por su cuenta.
![image](tool_pgplin23.png)

Llevamos las claves públicas de Danny O'Brien, por ejemplo, tiene un certificado caducado o revocado y uno certificado válido Seleccione el certificado válido haciendo clic en el cuadro de la izquierda y luego presione el botón OK.
![image](tool_pgplin24.png)

En algunos casos, una persona puede tener más de un certificado, y todos son válidos. Tenga en cuenta que es posible que cualquier persona cargue un certificado público para cualquier otra persona, y que una de estas claves puede no pertenecer a la persona propietaria de la dirección de correo electrónico asociada. En este caso, la verificación de la huella dactilar es extremadamente importante.

Aparecerá una pequeña ventana de notificación que le informará si tuvo éxito, y Enigmail Key Manager ahora le mostrará los certificados agregados:
![image](tool_pgplin25. png)

### 4.0 Envío de correo cifrado PGP

Ahora enviará su primer correo cifrado a un destinatario. En la ventana principal de Mozilla Thunderbird, haga clic en el botón "Escribir". Se abrirá una nueva ventana.

Escriba su mensaje e ingrese un destinatario. Para esta prueba, seleccione un destinatario cuya clave pública ya tiene. Enigmail detectará esto y cifrará automáticamente el correo electrónico (se puede decir que se codificará con la llave dorada en la parte inferior derecha del correo electrónico).
![image](tool_pgplin26.png)

** Tenga en cuenta que El asunto no será encriptado, así que elija algo inocuo, como "hola." **

Cuando haga clic en el botón "Enviar ", se le dará una ventana para ingresar la contraseña de su PGP Llave. Recuerde que esto es diferente de su contraseña de correo electrónico.

Ingrese su contraseña y luego haga clic en el botón "OK" y su correo electrónico será encriptado y enviado.

El cuerpo del correo electrónico fue encriptado y transformado. Por ejemplo, nuestro texto anterior, se convirtió a esto:
![image](tool_pgplin27.png)

### 4.1 Recepción de correo cifrado PGP

Vaya a pasar por lo que sucede cuando recibe correos cifrados. Primero, haga clic en el mensaje.

Se abre una pequeña ventana que le solicita la contraseña de la clave PGP. Recuerde: no ingrese su contraseña de correo electrónico. Haga clic en el botón "Aceptar".
![image](tool_pgplin28.png)

Now el mensaje aparecerá descifrado
![image](tool_pgplin29.png)

### 5.0 Revocando la clave PGP

** a) Revocar su clave PGP a través de la interfaz Enigmail **

Las claves PGP generadas por Enigmail expiran automáticamente después de cinco años. Por lo tanto, si pierde todos sus archivos, puede esperar que la gente sepa pedirle otra clave una vez que la clave haya expirado.

Podría tener una buena razón para desactivar la clave PGP antes de que caduque. Quizás desee generar una clave PGP nueva y más sólida. La forma más fácil de revocar su propia clave PGP en Enigmail es a través del Enigmail Key Manager. Haga clic derecho en su clave PGP (está en negrita), y seleccione la opción "Revocar clave".
![image](tool_pgplin30.png)

Se abrirá una ventana que le permite saber lo que sucede y preguntando para tu confirmacion. Haga clic en el botón "Revocar clave".
![image](tool_pgplin31.png)

Se abre la ventana de contraseña, ingrese su contraseña para la clave PGP y haga clic en el botón "OK".

Now se abrirá una nueva ventana que le informa que tuvo éxito. Haga clic en el botón "Aceptar".

Cuando regrese a la ventana de Administración de claves de Enigmail, notará un cambio en su clave PGP. Ahora aparece atenuado y en cursiva.
![image](tool_pgplin32.png)

** b) Revocación de una clave PGP con un certificado de revocación **

Como se mencionó anteriormente, las claves PGP generadas por Enigmail caduca automáticamente después de cinco años. Entonces, si pierde todos sus archivos, puede estar seguro de que la gente sabrá pedirle otra clave una vez que la llave haya expirado.

Como mencionamos anteriormente, es posible que tenga una buena razón para desactivar la clave PGP antes de que caduque.

De forma similar, otros podrían tener buenas razones para revocar una clave existente.

Es posible que recibas certificados de revocación de amigos como un aviso de que quieren revocar su clave.

En la sección anterior, habrás notado que Enigmail genera e importa un certificado de revocación internamente cuando utiliza Enigmail Key Manager para revocar una clave. Como ya tiene un certificado de revocación, usará el que generó anteriormente para revocar su propia clave.

Comience con Enigmail Key Manager y haga clic en el menú "Archivo" y seleccione "Importar claves del archivo. "
![image](tool_pgplin33.png)

Se abrirá una ventana para que pueda seleccionar el certificado de revocación. Haga clic en el archivo y haga clic en el botón "Abrir". Recibirá una notificación de que el certificado se importó con éxito y de que se revocó una clave. Haga clic en el botón "Aceptar".
![image](tool_pgplin34.png)

Una vez que haga clic en el botón "OK, volverá al Enigmail Key Manager y verá el certificado. revocado en gris y en cursiva.
![image](tool_pgplin35.png)

Si la clave que revocó es la suya y previamente ha cargado su clave pública en los servidores de claves, querrá volver a cargar el archivo. ahora, la clave revocada para los servidores de claves, para que otros vean que ya no la usan más.

Ahora que tiene todas las herramientas adecuadas, intente enviar su propio correo electrónico cifrado con PGP.