[Title]: # ()
[Order]: # (0)

# PGP PARA LA GUÍA DE HERRAMIENTAS MAC O SX

## PGP para Mac O SX Guía de herramientas
Email encriptado para Mac

**Lección para leer:** [Correo electrónico](umbrella://lesson/email)  
**Ubicación de descarga:**
- [GPG Suite](https://gpgtools.org/)
- [Mozilla Thunderbird](https://www.mozilla.org/thunderbird/)
- [Enigmail](https://www.enigmail.net/home/index.php)

**Requisitos de computadora:** Una conexión a Internet, una computadora con Mac OS X, una cuenta de correo electrónico  
**Versión utilizada en esta guía:** 
- GPG Suite Beta 4
- Mozilla Thunderbird 31.2.0
- Enigmail 1.7.2

**Licencia:** Software Libre; combinación de licencias de Software Libre  
**Nivel:** Avanzado  
**Otra lectura:** [http://support.gpgtools.org/](http://support.gpgtools.org/)  
**Tiempo requerido:** 30-60 minutos

**El uso de PGP le dará:**
- La capacidad de proteger sus comunicaciones de correo electrónico para que nadie las lea, excepto sus destinatarios.
- La capacidad de demostrar que un correo electrónico provino de una persona en particular, en lugar de ser un mensaje falso enviado por otro remitente(de lo contrario, es muy fácil que se fabrique el correo electrónico). Ambas son defensas importantes si está siendo objeto de vigilancia o desinformación.

### 1.0 Antes de comenzar

Para usar Pretty Good Privacy(PGP), deberá instalar algún software adicional que lo trabaja con tu programa de correo electrónico actual. También necesitarás crear una clave privada, que mantendrás en privado. La clave privada es lo que usará para descifrar los correos electrónicos que se le envían, y para firmar digitalmente correos electrónicos que envíe para mostrar que realmente provienen de usted. Finalmente, aprenderá cómo distribuir su clave pública, una pequeña porción de información que otros necesitarán saber antes de poder enviarle correos encriptados, y que pueden usar para verificar los correos electrónicos que envía.

Esta guía mostrará cómo usar PGP con una Mac de Apple(pero no con iPad o iPhone), ya sea con el programa de correo incorporado de la Mac o con Mozilla Thunderbird, un popular programa alternativo de correo electrónico.

No puede usar PGP directamente con un servicio de correo electrónico web como Gmail, Hotmail, Yahoo! Correo o Outlook Live. Aún puede usar su dirección de correo web; solo tendrá que configurarlo con el programa Thunderbird en su computadora.

**Tenga en cuenta que ambos extremos de la conversación por correo electrónico deben estar usando un software compatible con PGP para que funcione.**

La gente lo hará Normalmente, use esto solo en sus dispositivos personales, no en dispositivos compartidos. Afortunadamente, PGP está disponible para la mayoría de las computadoras de escritorio y dispositivos móviles, y puede indicarles estas guías para ayudarlos a configurar su propia versión. Esta guía es para usuarios de Mac.

### 2.0 Instalar GPGTools en su Mac

PGP es un estándar abierto, lo que significa que puede usarlo más de un software. El software que vamos a usar para PGP se llama GPG Suite, de GPG Tools, porque funciona en Mac, es gratis para que cualquiera lo use, y es de código abierto: el código fuente subyacente está disponible para que cualquiera pueda verificar si hay errores. y puertas traseras.

Una vez instalado GPG Suite, puede configurar sus llaves por primera vez y luego habilitar PGP en Apple Mail y, opcionalmente, Thunderbird.

**Paso 1: Instalar el programa.**

Primero, vaya a [https://www.gpgtools.org/](https://www.gpgtools.org/) en su navegador y seleccione "Descargar GPG Suite".
![image](tool_pgposx1.png)

Tienes una imagen de disco en la que puedes hacer clic para instalar el software. Si no estás acostumbrado a instalar software de terceros en tu computadora, pregúntale a un experto en Mac cercano: es un paso que la mayoría de los expertos en tecnología pueden ayudarlo, incluso si no conocen PGP o el cifrado.
![image](tool_pgposx2.png)

Haciendo clic en instalar le dará una lista de las herramientas que se agregarán a su computadora.
![image](tool_pgposx3.png)

**_¿Es exactamente que estoy instalando aquí?_**

Estas son herramientas que en su mayoría funcionarán detrás de escena para que más de un programa en su Mac pueda usar PGP. Piense en ellos como programas que otros programas pueden usar, en lugar de aplicaciones que usará directamente. GPGMail permite que Apple Mail envíe y lea correos electrónicos de PGP, GPG Keychain Access le permite mantener sus claves privadas y públicas de la misma manera que puede guardar otras contraseñas en su Mac.

GPGServices opcionalmente agrega una función a OS X para permitirle usar PGP directamente en programas distintos al correo electrónico (por ejemplo, en un procesador de textos). GPGPreferences es para cambiar la configuración de PGP en las preferencias de Apple. Finalmente, MacGPG2 es la herramienta básica que cualquier programa necesita usar para cifrar o firmar.

En octubre de 2014, el equipo de GPG Tools anunció que pronto cobrarían por GPGMail, la parte de su paquete que le permite usar GPG con la aplicación de correo de Apple. Este tutorial trata de usar GPG con Thunderbird, por lo que no usa ese componente. Solo puede usar la parte de costo cero de GPG Suite, como se describe aquí, si lo desea. Esta opción tiene el beneficio adicional de que todas estas herramientas son "software libre", lo que significa que todavía puede examinar, editar y redistribuir libremente el código fuente subyacente de GPG Mail, por lo que son aún más seguras. Para obtener más información, consulte las [Preguntas frecuentes de GPG Tools](https://gpgtools.org/news.html) sobre su decisión.


Haga clic en "Continuar" para instalar GPG Suite.
![image](tool_pgposx4.png)

Cuando la instalación esté completa, abra GPG Keychain(que se encuentra en su carpeta de aplicaciones) si no lo hace t se abre automáticamente y le solicita que genere sus claves PGP después de la instalación. Haga clic en "Nuevo" para generar sus claves PGP.
![image](tool_pgposx5.png)

**Paso 2: Cree su clave PGP**

A veces, cuando instala un nuevo software, su computadora le molestará con preguntas que no tienen una respuesta obvia, sin darle ningún consejo sobre cómo responder. Esta es una de esas veces.

Es importante que dediques un poco de tiempo a pensar en las respuestas que darás aquí, porque cambiar los detalles de tu clave PGP puede ser difícil más adelante, y si has elegido publicar tu clave en alguna parte, no podrás anular la publicación.(Todavía hay miles de claves públicas antiguas de la década de 1990 flotando, con los nombres y las antiguas direcciones de correo electrónico de las personas que las crearon en ese momento).

Las claves PGG contienen un nombre y una dirección de correo electrónico que vinculan la clave. La dirección de correo electrónico será una de las formas en que otros podrán descubrir qué clave usar cuando encripten un mensaje para usted.

**_¿Cuándo no debería poner mi nombre real o dirección de correo electrónico en mi clave PGP? ¿Cuándo no debería subir mi llave?_**

Para la mayoría de las personas, tiene sentido agregar una dirección de correo electrónico real a su llave y cargarla en los servidores de llaves públicas; así es como las personas encontrarán la llave correcta para usted . Pueden enviarle un correo electrónico directamente, y saber que se cifrará con la clave correcta, y cuando reciban un correo electrónico firmado por usted, la firma digital se marcará con su nombre.

Para algunas personas, sin embargo, lo hará No tiene sentido agregar tu nombre real a tu clave, por ejemplo, si tu modelo de amenaza significa que tener tu identidad adjuntada públicamente a tu clave (y la dirección de correo electrónico vinculada) no es una buena idea. Edward Snowden se comunicó con los periodistas que usaban PGP y una dirección de correo electrónico anónima antes de revelar su identidad; su clave PGP ciertamente no estaba marcada con su nombre.

**Cargar su clave es una práctica normal, pero puede revelar que está usando cifrado, incluso si no usa su propio nombre. Además, como veremos, otros pueden subir su clave y asociar su propia clave con ella, lo que implica que usted y ellos tienen una conexión. Eso puede ser dañino si te estás comunicando y no quieres que la gente lo sepa. También puede ser problemático si no te estás comunicando, pero tu atacante quiere que la gente piense que estás asociado.**

Es una guía aproximada: si estás pensando en usar un seudónimo en general, usa ese seudónimo (y correo electrónico alternativo) al etiquetar su clave. Si se encuentra en un entorno más peligroso, cuando no desea que la gente sepa que está utilizando PGP, o sabe con quién se está comunicando, no cargue su clave en los servidores de llaves públicos, y asegúrese de que la pequeña El grupo de personas con el que se está comunicando también sabe que no debe cargar su clave. Existen otras maneras de verificar las claves que no se basan en que estén disponibles en el servidor de claves públicas: consulte la guía de EFF para [Verificación de claves](https://ssd.eff.org/es/module/key-verification#overlay=en/node/37/) para obtener más información.

Haga clic en el cuadro "Cargar clave pública después de la generación" si desea permitir que otros encuentren su clave rápidamente para que puedan enviarle mensajes encriptados. Es como agregar su número de teléfono a un directorio telefónico público: no lo necesita, pero es conveniente para otros.

Antes de generar la clave, expanda "Opciones avanzadas." Puede dejar el comentario en blanco y salir el tipo de clave "RSA y RSA(predeterminado)." Pero asegúrese de cambiar el campo Longitud a 4096.
![image](tool_pgposx6.png)

**Su clave caducará en un momento determinado ; cuando eso sucede, otras personas dejarán de usarlo por completo para recibir correos electrónicos nuevos, aunque es posible que no reciba ninguna advertencia o explicación sobre por qué. Por lo tanto, es posible que desee marcar su calendario y prestar atención a este problema aproximadamente un mes antes de la fecha de vencimiento.**

Es posible prolongar el período de vigencia de una clave existente dándole una nueva fecha de vencimiento posterior o es posible reemplazarlo con una nueva clave creando uno nuevo desde cero. Ambos procesos pueden requerir el contacto con personas que le envían correos electrónicos y se aseguran de que obtengan la clave actualizada; el software actual no es muy bueno para automatizar esto. Así que haz un recordatorio por ti mismo; si no crees que puedas gestionarlo, puedes considerar configurar la clave para que nunca caduque, aunque en ese caso otras personas podrían tratar de usarlo cuando te contacten en el futuro, incluso si ya no lo haces. tiene la clave privada o ya no usa PGP.

Cuando esté listo, haga clic en el botón "Generar clave".

La computadora comenzará a generar su clave pública y privada. No debe tomar más de un par de minutos para terminar (lleva un tiempo porque para crear sus claves, su computadora necesita reunir números aleatorios. Piense en ello como si su computadora arrojara un par de dados muchas, muchas, muchas veces.)
![image](tool_pgposx7.png)

Cuando haya terminado de generar su clave, la verá en la lista de acceso de llavero de GPG. Puede hacer doble clic en su clave para ver información al respecto, incluida su "huella digital", una forma única de identificar su clave PGP.

Ahora es un buen momento para generar un certificado de revocación. (Un certificado de revocación es un archivo que puede generar que anuncia que ya no confía en esa clave. La genera cuando todavía tiene la clave secreta y la guarda para cualquier desastre futuro). En el futuro, si alguna vez se preocupa de que su clave privada ha sido copiada por alguien, accidentalmente elimina o pierde su clave privada, o usted olvida su frase de contraseña, puede decir a todos que ha sido revocada, o cancelada, mediante el uso de un certificado de revocación.

Es mejor crear uno ahora, porque necesita la clave privada y la frase de contraseña para crear un certificado de revocación. Si lo deja hasta más tarde, puede perder uno u otro, y entonces será demasiado tarde. Así que cree un certificado haciendo clic en su clave, seleccionando la entrada del menú "Clave", y luego "Crear certificado de revocación." Se le pedirá que guarde el archivo en algún lugar. Es posible que desee conservarlo con una copia de seguridad de la clave(consulte el siguiente paso).

**Paso 3: haga una copia de seguridad de su clave PGP**

Si pierde el acceso a su clave privada, ganó podrá descifrar cualquier correo PGP entrante o su correo anterior. Por otro lado, desea mantener su clave privada lo más segura posible.

Es posible que desee guardar una copia de seguridad en una llave USB, que se mantiene oculta de forma segura. Solo lo necesitarás si pierdes tu llave original, pero para tu seguridad querrás mantenerla fuera de las manos de tus posibles atacantes.

**_¿Se pierde todo si mis atacantes se apoderan de mi llave privada PGP?_**

¿Qué sucede si le roban su Mac o le quitan la clave de respaldo? ¿Eso significa que sus mensajes PGP son vulnerables? No: si ha elegido una buena frase de contraseña y nadie ha podido saber de qué se trata, aún debería estar protegido en su mayoría. Para estar seguro, es posible que desee revocar su clave anterior y crear una nueva clave PGP. Esto no impedirá que su clave antigua pueda descifrar su correo electrónico anterior, pero desalentará a otras personas de usar la clave anterior para sus nuevos correos electrónicos.

Para hacer una copia de seguridad de su clave, abra el Acceso llavero GPG. Seleccione su clave y haga clic en "Exportar" en la barra de herramientas. Coloque su unidad USB en la máquina y selecciónela en la parte "Where" del diálogo "Guardar como ...". Marca la casilla de verificación "Permitir exportación de clave secreta".

**OPCIÓN A) Configuración de Apple Mail**

Cuando abres Apple Mail por primera vez, verás un asistente de primera ejecución que te ayuda a configurar tu dirección de correo electrónico. Complete su nombre, dirección de correo electrónico y contraseña de su correo electrónico y haga clic en "Crear".
![image](tool_pgposx8.png)

**Asistente de configuración de la cuenta de correo**

Si usa los recursos populares servicios gratuitos de correo electrónico como Gmail, Mail debe poder detectar automáticamente su configuración de correo electrónico cuando hace clic en Continuar. Si no es así, es posible que deba configurar manualmente sus configuraciones de IMAP y SMTP. Hable con la empresa que utiliza para el correo electrónico, o pregúntele a alguien técnico que esté familiarizado con su proveedor de correo electrónico(por lo tanto, una persona de TI en el trabajo o un amigo técnico que use el mismo ISP que usted. No necesitan saber acerca de PGP, pero puede preguntarles "¿Pueden configurar Apple Mail para mí?").
![image](tool_pgposx9.png)

**Configuración automática de cuenta de correo**

Cuando redacta un mensaje nuevo, hay dos iconos justo debajo del campo Asunto. Hay un candado(encriptar el correo electrónico) y una estrella(firmar digitalmente el correo electrónico). Si el candado está cerrado significa que este correo electrónico estará encriptado, y si la estrella tiene un cheque, significa que este correo electrónico se firmará digitalmente.

**Envío de correo electrónico firmado o cifrado de PGP**
![image](tool_pgposx10.png)

Puede siempre firmar su correo electrónico, incluso si el destinatario no usa PGP. Debido a que la firma digital de correos electrónicos requiere su clave secreta, Mail abrirá una ventana que le pedirá su frase de contraseña la primera vez que firme un correo electrónico.

Sólo puede cifrar correos electrónicos si la persona que está enviando utiliza PGP y usted tiene la clave pública de esa persona . Si el icono del candado de cifrado está desbloqueado y atenuado para que no pueda hacer clic en él, significa que primero debe importar la clave pública del destinatario. O solicíteles que se lo envíen, o use la aplicación de Acceso a Llaveros GPG para encontrar la llave de un servidor de llaves público.

Para estar absolutamente seguro, deberá verificar las llaves que obtiene del servidor de llaves o de su colega. Consulte la guía de EFF para [Verificación de clave](https://ssd.eff.org/en/module/key-verification#overlay=en/node/37/) para obtener más información.

**OPCIÓN B) Uso de PGP con Mozilla Thunderbird**

Este tutorial muestra cómo usar GPG con el cliente de correo Thunderbird gratuito y de código abierto de Mozilla, junto con el complemento Enigmail para el cifrado del correo electrónico.

Primero, descargue Thunderbird de [https://www.mozilla.org/thunderbird](https://www.mozilla.org/thunderbird), monte la imagen de disco como lo hizo con las Herramientas de GPG, y arrastre el Thunderbird a Aplicaciones. Cuando lo abra por primera vez, le preguntará si desea configurarlo como su cliente de correo electrónico predeterminado. Continúe y haga clic en "Establecer como predeterminado."
![image](tool_pxposx11.png)

A continuación, verá el asistente de la primera ejecución. Para configurar su dirección de correo electrónico existente, haga clic en "Omitir esto y use mi correo electrónico existente." Luego ingrese su nombre, dirección de correo electrónico y contraseña en su cuenta de correo electrónico.
![image](tool_pgposx12.png)

Si utiliza servicios populares de correo electrónico gratuito como Gmail, Thunderbird debería poder detectar automáticamente su configuración de correo electrónico al hacer clic en Continuar. Si no es así, es posible que deba configurar manualmente sus configuraciones de IMAP y SMTP; solicite ayuda a su ISP o a un amigo técnico que sepa cómo configurar el correo electrónico. A veces, Thunderbird solo puede adivinar la configuración correcta.

**Si usa la autenticación de dos factores con Google(¡y según su modelo de amenaza probablemente debería hacerlo!) No puede usar su contraseña estándar de Gmail con Thunderbird. En su lugar, deberá crear una nueva contraseña específica de la aplicación para que Thunderbird acceda a su cuenta de Gmail. Consulte [la propia guía de Google](https://support.google.com/mail/answer/1173270?hl=en) para hacer esto.**
![image](tool_pgposx13.png)

Después de usted Terminó de configurar Thunderbird para revisar su correo electrónico, haga clic en "Listo." Luego haga clic en "Bandeja de entrada" en la parte superior izquierda para cargar sus correos electrónicos.

Ahora que ha instalado y configurado Thunderbird para trabajar con su correo electrónico , debe instalar [Enigmail](https://www.enigmail.net/home/index.php), el complemento GPG para Thunderbird. En Thunderbird, haga clic en el ícono de menú en la esquina superior derecha y elija Complementos.
![image](tool_pgposx14.png)

Busque _enigmail_ en el cuadro de búsqueda en la esquina superior derecha.
![image](tooL_pgposx15.png)

Haga clic en el botón Instalar al lado de la extensión Enigmail para descargar e instalar Enigmail. Cuando termine, haga clic en "Reiniciar ahora" para reiniciar Thunderbird.

La primera vez que ejecute Thunderbird con Enigmail habilitado, se abre el Asistente de configuración de OpenPGP. Haga clic en "Cancelar". En su lugar, configuraremos manualmente Enigmail.

Haga clic en el botón de menú, desplace el mouse sobre Preferencias y seleccione Configuración de la cuenta.
![image](tool_pgposx16.png)

Vaya a OpenPGP Security lengüeta. Asegúrese de que "Habilite el soporte de OpenPGP (Enigmail) para esta identidad" esté marcado. "Usar ID de clave de OpenPGP específico" debe seleccionarse, y si su clave no está ya seleccionada, puede hacer clic en "Seleccionar clave" para seleccionarla.

También debe marcar "Firmar mensaje no cifrado por predeterminado","Firme mensajes cifrados de forma predeterminada" y "Usar PGP/MIME de forma predeterminada, "pero no (para la mayoría de la gente)" Cifre los mensajes por defecto."

Si la mayoría de las personas que el correo electrónico use PGP (o le gustaría animarlos a que lo hagan), es posible que desee encriptar de forma predeterminada. Sería ideal cifrar todos los correos electrónicos que envíe, pero eso no siempre es posible. Recuerde que solo puede enviar correos electrónicos cifrados a otras personas que usan PGP, y necesita tener sus claves públicas en su llavero. Para la mayoría de las personas, la elección manual de encriptar cada correo electrónico que envíe probablemente funcione mejor.
![image](tool_pgposx17.png)

A continuación, haga clic en "OK" para guardar todas las configuraciones.

Felicitaciones, ¡ahora tienes configurados Thunderbird y Enigmail! Aquí hay un par de consejos rápidos:

- Puede hacer clic en el botón de menú, colocar el puntero sobre OpenPGP y abrir Key Management para ver el administrador de claves de PGP que está incorporado en Enigmail. Es muy similar al acceso llavero GPG, y es tu elección la que utilizas.
- Cuando redacta un mensaje nuevo, hay dos iconos en la esquina inferior derecha de la ventana: un lápiz (correo electrónico de firma digital) y una clave (cifra de correo electrónico). Si los íconos son dorados, significa que están seleccionados, y si son plateados significa que no están seleccionados. Haga clic en ellos para alternar la firma y el cifrado del correo electrónico que está escribiendo.
![image](tool_pgposx18.png)
