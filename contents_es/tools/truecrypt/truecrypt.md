[Title]: # ()
[Difficulty]: # (Principiante)
[Order]: # (0)

# TRUECRYPT GUÍA DE HERRAMIENTAS 

## Guía de la herramienta TrueCrypt 

Secure File Storage 

**Lección para leer: [Protección de archivos](umbrella://lesson/protect-files)**
**Ubicación de descarga:** [https://truecrypt.ch/downloads/](https://truecrypt.ch/downloads/) 
**Requisitos de la computadora:** 

- Una conexión a Internet, Windows 2000 / XP / 2003 / Vista / 7, Mac OS X o GNU Linux (Esta guía se ejecuta en Windows) 
- Derechos de administrador necesarios para la instalación o para crear volúmenes pero no para acceder a volúmenes existentes 
- **Versión utilizada en esta guía:** 7.1a (La página web de desarrolladores ofrece una nueva versión 7.2 de TrueCrypt con algunas funcionalidades eliminadas. A pesar de esta nueva versión, le recomendamos que continúe usando la versión anterior 7.1a.) 
- **Licencia:** Gratis y de código abierto Software - ** Nivel: ** Avanzado 
- **Otra lectura:** [http://andryou.com/truecrypt/docs/index.php](http://andryou.com/truecrypt/docs/index .php) 
- **Tiempo requerido:** 30-60 minutos 
- **El uso de TrueCrypt le dará:** 
- La capacidad t o Proteja eficazmente sus archivos de intrusos o acceso no autorizado 
- La capacidad de almacenar de manera fácil y segura copias de sus archivos importantes 
- **NOTA: TrueCrypt está actualmente sin mantenimiento, lo que podría tener implicaciones de seguridad.**
![imagen](tool_truecrypt1.png) 

### 1.0 Antes de comenzar 
Truecrypt mantiene sus archivos seguros al evitar que alguien sin la contraseña correcta los abra. Funciona como una caja fuerte electrónica, creando un contenedor cifrado (llamado volumen) en su computadora o disco duro, que puede poner tantos archivos como desee. ¡Si olvida su contraseña, perderá acceso a sus datos! 

Por favor, tenga en cuenta que el uso del cifrado es ilegal en algunos países. 

TrueCrypt ofrece la capacidad de crear un volumen cifrado estándar o un volumen oculto. Cualquiera de los dos mantendrá sus archivos confidenciales, pero un volumen oculto le permite ocultar su información importante detrás de datos menos confidenciales para protegerlo, incluso si se ve obligado a revelar su volumen TrueCrypt. Esta guía explica ambos volúmenes en detalle. Cómo instalar TrueCrypt y Crear volúmenes estándar 

tCómo montar el volumen estándar tCómo realizar una copia de seguridad de su volumen tVersiones ocultas Portable TrueCrypt 

**NOTA: TrueCrypt no está actualizado, lo que podría tener implicaciones de seguridad.** 

### 2 Cómo instalar TrueCrypt y crear volúmenes estándar 

### 2.0 Cómo instalar TrueCryrpt 

**Paso 1.** 
Haga doble clic en _TrueCrypt Setup 7.1a.exe_; el cuadro de diálogo _Open File - Security Warning_ puede aparecer. Si es así, haga clic en "Siguiente" para activar la pantalla TrueCrypt _License_. 

**Paso2.** 
Marque la casilla Acepto y acepto estar sujeto a la opción _license terms_ para habilitar el botón Aceptar; haga clic en "Aceptar" para activar la siguiente pantalla:
![image](tool_truecrypt2.png) 

- Modo de instalación: esta opción es para usuarios que no desean ocultar el hecho de que usan TrueCrypt en su computadora. 

- Modo extracción: esta opción es para usuarios que desean llevar una versión portátil de TrueCrypt en una memoria USB y no desean tener TrueCrypt instalado en su computadora. 

**Nota:** Algunos de los las opciones (por ejemplo, la partición completa y el cifrado del disco) no funcionarán cuando se extraiga TrueCrypt solamente. 

**Nota:** Aunque se recomienda el modo _Install_ predeterminado aquí, puede seguir usando TrueCrypt en modo portátil más adelante. 

**Paso 3. Haga clic en** "Siguiente " para activar la siguiente pantalla:
![image](tool_truecrypt3.png) 

**Paso 4.** Haga clic en "Instalar "para activar la pantalla _Instalación_ para comenzar a instalar TrueCrypt en su sistema. 

**Paso 5.** Haga clic en "Ok" y luego "Finalizar" para activar la siguiente pantalla:![image](tool_truecrypt4. png) 

**Paso 6.** Haga clic en "Sí" para completar la instalación de TrueCrypt. 

**Nota:** Se recomienda encarecidamente a todos los usuarios que consulten la [documentación de ayuda de TrueCrypt](http: //andryou.com/truecrypt/docs/index.php) después de completar este tutorial. 

### 2.1 Acerca de TrueCrypt 

TrueCrypt es un programa que protege sus archivos evitando que cualquiera sin la contraseña correcta pueda acceder a ellos . Funciona como una caja de seguridad electrónica, lo que le permite bloquear sus archivos para que solo alguien con la contraseña correcta pueda abrirlos. TrueCrypt funciona al permitirle configurar _volumes_ o secciones en su computadora donde puede almacenar archivos de manera segura. Cuando crea datos en, o mueve datos a estos volúmenes, TrueCrypt encriptará automáticamente esa información. Cuando abre o saca sus archivos, los descifra automáticamente para usarlos. Este proceso se denomina cifrado _en el momento_. 

### 2.2 Cómo crear un volumen estándar 

TrueCrypt le permite crear dos tipos de volúmenes: _Hidden_ ​​y _Standard_. En esta sección, aprenderá a crear un _Volumen estándar_ en el que almacenar sus archivos. Para comenzar a usar TrueCrypt para crear un _Volumen estándar_, realice los siguientes pasos: 

**Paso 1.** Doble haga clic en el ícono de TrueCrypt o seleccione 

**Inicio > Programas > TrueCrypt > TrueCrypt** para abrir TrueCrypt. 

**Paso 2.** Seleccione una unidad de la lista en el panel TrueCrypt de la siguiente manera: 
![image](tool_truecrypt5.png) 

**Paso 3.** Haga clic en "Crear volumen" para activar _TrueCrypt Volume Creation Wizard_ de la siguiente manera: 
![image](tool_truecrypt6.png) 

Hay tres opciones para encriptar un _Tomo estándar_. En esta guía, usaremos la opción Crear un contenedor de archivos encriptados. Consulte la documentación de [**TrueCrypt**](www.truecrypt.org/docs/) para obtener la descripción de las otras dos opciones. 

**Paso 4.** Haga clic en "Siguiente" para activar el Pantalla siguiente:
![image](tool_truecrypt7.png) 

La ventana TrueCrypt Volume Creation Wizard Volume Type_ le permite especificar si prefiere crear un volumen _Standard_ o _Hidden_ **_TrueCrypt_**. 

Para obtener más información sobre _Cómo crear un volumen oculto_, consulte la sección Volúmenes ocultos más abajo. 

**Paso 5.** Compruebe la opción _Standard TrueCrypt Volume_. 

**Paso 6.** Haga clic en "Siguiente" para activar la siguiente pantalla: 
![Image](tool_truecrypt8.png) 
Puede especificar dónde desea almacenar su _Standard Volume_ en la pantalla _Volume Creation Wizard - Volume Location_. Este archivo se puede almacenar como cualquier otro archivo. 

**Paso 7.** Ingrese el nombre del archivo en el campo de texto o haga clic en "Seleccionar archivo" para activar la siguiente pantalla:
![image](tool_truecrypt9.png) 

**Nota:** Un Volumen TrueCrypt está contenido dentro de un archivo normal. Esto significa que se puede mover, copiar o incluso eliminar! Debe recordar tanto la ubicación como el nombre del archivo. Sin embargo, debe elegir un nuevo nombre de archivo para el volumen que crea. En este tutorial, crearemos nuestro Volumen estándar en la carpeta **Mis documentos**, y nombraremos el archivo _Mi volumen_ como se muestra en _figura 8_ anterior. 

**Sugerencia:** Puede usar cualquier nombre de archivo y extensión de archivo. Por ejemplo, puede asignarle un nombre a su Volume Volume _recipes.doc_, de modo que se vea como un _Word_ document, o _holidays.mpg_, de modo que se vea como un archivo de película. Esta es una forma de ayudar a ocultar la existencia de su Volumen estándar. 

**Paso 8.** Haga clic en "Guardar" para cerrar la ventana _Especificar ruta_ y _Archivo_ y volver a la ventana _Ajuste de creación de volumen_ como sigue:
![image](tool_truecrypt10.png) 

**Paso 9.** Haga clic en "Siguiente". 

### 2.3 Cómo crear un volumen estándar en una memoria USB 
Para crear TrueCrypt _Standard Volume_ en un dispositivo de memoria USB, realice los pasos 1 a 7 en la sección 2.2 Cómo crear un volumen estándar, donde activa la pantalla _Seleccione un volumen TrueCrypt_. En lugar de elegir _My Documents_ como la ubicación de su archivo, navegue hacia y luego **elija** su dispositivo de memoria USB. Luego, ** ingrese ** un nombre de archivo y cree el _Tamaño estándar_ allí. 

### 2.4 Cómo crear un Volumen estándar (continuación)
En esta etapa, está listo para elegir un método de cifrado específico (o _algorithm_ como se hace referencia en la pantalla) para codificar los datos que se almacenarán en su _Volumen estándar_.
![image](tool_truecrypt11.png) 

**Nota:** Puede dejar el opciones predeterminadas aquí a medida que aparecen. Todos los algoritmos presentados en las dos opciones aquí se consideran seguros. 

**Paso 10.** Haga clic en "Siguiente" para activar la pantalla _TrueCrypt Volume Creation Wizard_ de la siguiente manera:
![Image](tool_truecrypt12.png ) 

El panel _Volume Size_ le permite especificar el tamaño de _Standard Volume_. En este ejemplo, se establece en 10 megabytes. Sin embargo, puede especificar un tamaño diferente. Tenga en cuenta el tamaño de los documentos y tipos de archivos que desea almacenar y, a continuación, establezca un tamaño de volumen adecuado para ellos. 

**Sugerencia:** Si desea hacer una copia de seguridad de su Volumen estándar en un CD más adelante, luego debe establecer el tamaño en 700 MB o menos. 

**Paso 11.** Escriba su tamaño de volumen específico en el campo de texto, y luego haga clic en "Siguiente" para activar la siguiente pantalla:
![image](tool_truecrypt13.png) 

**Importante:** Elegir una contraseña segura y segura es una de las tareas más importantes que realizará al crear un _Tamaño estándar_. Una buena contraseña protegerá su volumen encriptado, y cuanto más fuerte sea la contraseña que elija, mejor. No tiene que crear sus propias contraseñas, ni siquiera recordarlas, si utiliza un programa de generación de contraseñas como KeePass. Consulte la **[lección de KeePass](umbrella://lesson/keepassx)**, para obtener más información sobre la creación y el almacenamiento de contraseñas. 

**Paso 12.** Escriba su contraseña y luego vuelva escriba su contraseña en los campos _Confirmar_ texto. 

**Importante:** El botón _Next_ permanecerá deshabilitado hasta que coincidan las contraseñas en ambos campos de texto. Si su contraseña no es particularmente segura o segura, verá una advertencia que le informará sobre esto. Considera cambiarlo! Aunque **TrueCrypt** seguirá funcionando con la contraseña que haya elegido, sus datos pueden no ser muy seguros. 

**Paso 13.** Haga clic en "Siguiente " para activar la siguiente pantalla: 
![image](tool_truecrypt14.png) 

TrueCrypt ahora está listo para crear un _Standard Volume_. Mueva su mouse al azar dentro de la ventana _TrueCrypt Volume Creation Wizard_ por unos segundos. Cuanto más tiempo mueva el mouse, mejor será la calidad de la clave de encriptación. 

**Paso 14.** Haga clic en "Formato" para comenzar a crear su volumen estándar. TrueCrypt ahora creará un archivo llamado _My Volume_ en la carpeta _My Documents_ como se especificó anteriormente. Este archivo contendrá TrueCrypt _Standard Volume_, 10 megabytes de tamaño, que puede usar para almacenar sus archivos de manera segura. 

Después de que se haya creado con éxito un _Standard Volume_, aparecerá el siguiente cuadro de diálogo:
![Image]( tool_truecrypt15.png) 

**Paso 15.** Haga clic en "OK " para completar la creación de su _Volumen estándar_ y regrese a la consola TrueCrypt. 

**Paso 16.** Haga clic en "Salir" para cerrar "TrueCrypt Volume Creation Wizard". 

### 3 Cómo montar el volumen estándar 

### 3.0 Cómo montar un volumen estándar 

En TrueCrypt, montar un _Volumen estándar_ se refiere a hacer el volumen estándar disponible para su uso. En esta sección, aprenderá cómo montar su volumen estándar recién creado. Para comenzar a montar su volumen estándar, realice los siguientes pasos: 

**Paso 1.** Haga doble clic en el icono TrueCrypt 
**Seleccione Inicio > Programas > TrueCrypt > TrueCrypt** para abrir TrueCrypt. 

**Paso 2.** Seleccione cualquier unidad de la lista de la siguiente manera:
![Image](tool_truecrypt16.png) En este ejemplo, el Volumen estándar se montará como la unidad M: 

**Nota:** En la imagen de arriba, se ha seleccionado la unidad _M: _ para montar el _valor estándar_; sin embargo, puede elegir otra unidad en la lista. 

**Paso 3.** Haga clic en "Seleccionar archivo ..." 

La pantalla Seleccionar un Volumen TrueCrypt aparecerá de la siguiente manera:
![imagen ](tool_truecrypt17.png) 

**Paso4.** Seleccione el archivo de volumen estándar que ha creado, luego haga clic en "Abrir" para cerrar _figure 2_ y regrese a la consola de TrueCrypt.

**Paso 5.** Haga clic en "Montar" para activar la pantalla _Introduzca la contraseña de_solicitud_ de la siguiente manera:
![Image](tool_truecrypt18.png) 

**Paso 6.** Escriba la contraseña en la _Contraseña_: campo de texto. 

**Paso 7.** Haga clic en "Aceptar" para comenzar a montar el _Tamaño estándar_. 

**Nota:** Si la contraseña que escribió es incorrecta, TrueCrypt le preguntará que vuelva a escribir su contraseña y haga clic en "OK ". Si la contraseña es correcta, _Standard Volume_ se montará de la siguiente manera:
![Image](tool_truecrypt19.png) 

**Paso 8.** Haga doble clic en la entrada resaltada en TrueCrypt o haga doble clic en la unidad correspondiente Carta en la pantalla _My Computer_ para acceder al _Standard Volume_ (ahora montado en la unidad _M:_ en su computadora).
![image](tool_truecrypt20.png) 

**Nota:** Acabamos de montar correctamente el volumen estándar de Mi volumen en un disco virtual _M: _. Este disco virtual se comporta como un disco real, excepto que está completamente encriptado. Todos los archivos se cifrarán automáticamente cuando los copie, mueva o guarde en este disco virtual (un proceso conocido como cifrado sobre la marcha). Puede copiar archivos desde y hacia el _ Volumen estándar_ del mismo modo que los copiaría a cualquier disco normal (por ejemplo, arrastrándolos y soltándolos). Cuando mueve un archivo fuera del _Volumen estándar_, se descifra automáticamente. Por el contrario, si mueve un archivo al _Tamaño estándar_, TrueCrypt lo cifra automáticamente. Si su computadora falla o se apaga repentinamente, TrueCrypt cerrará inmediatamente el "Tamaño estándar".

**Importante:** Después de transferir los archivos al volumen TrueCrypt, asegúrese de que no queden rastros de los archivos en la computadora o memoria USB de la que provienen. Consulte **[Lección de eliminación segura](umbrella://lesson/safely-deleting)**.

### 3.1 Cómo desmontar el volumen estándar 
En TrueCrypt, a _dismount_ a _Standard Volume_ simplemente significa hacer que un volumen no esté disponible para su uso. 

Para cerrar o desmontar un _Volumen estándar_ y hacer que sus archivos sean accesibles solo para alguien con una contraseña, realice los siguientes pasos: 

**Paso 1.** Seleccione el volumen de la lista de volúmenes montados en la ventana principal de TrueCrypt de la siguiente manera:
![image](tool_truecrypt21.png)

**Paso 2.** Haga clic en "Desmontar " para desmontar o cerrar su estándar TrueCrypt volumen. 

**Importante:** Asegúrese de desmontar su volumen TrueCrypt antes de poner su computadora al modo _Standby_ o _Hibernate_. Mejor aún, apague siempre su computadora o computadora portátil si planea dejarla desatendida. Esto evitará que alguien pueda obtener su contraseña de volumen. 

Para recuperar un archivo almacenado en su volumen estándar una vez que lo haya cerrado o desmontado, tendrá que volver a montarlo. 

### 4.0 Cómo Hacer una copia de seguridad de tu volumen 
Recomportar tus documentos, archivos y carpetas con regularidad es fundamental. Copia de seguridad de su volumen TrueCrypt es vital y (afortunadamente) fácil de hacer. No olvide que su volumen debe desmontarse antes de realizar una copia de seguridad. 

**Paso 1.** Navegue hasta su archivo _Standard Volume_ (en la imagen siguiente, se encuentra en la carpeta _My Documents_).
![image](tool_truecrypt22.png) 

**Paso 2.** Guarde el archivo en un dispositivo de memoria externo, como un CD, DVD o una memoria USB. 

**Consejo:** Si tiene grandes cantidades de datos que desea encriptar y archivar repetidamente, ¿por qué no crear un nuevo _Standard Volume_ que tenga el mismo tamaño que un CD o DVD? Esto podría utilizarse como una técnica de almacenamiento segura. Antes de hacer una copia de seguridad del volumen estándar en un dispositivo extraíble, asegúrese de que el tamaño del dispositivo corresponda al tamaño de su volumen. 

### 5.0 Acerca de los volúmenes ocultos 
En TrueCrypt, se almacena _Hidden Volume_ dentro de su _Standard Volume_ encriptado, pero su existencia está oculta. Incluso cuando "monta" o abre su volumen estándar, no es posible encontrar o probar la existencia del volumen oculto. Si se ve obligado a revelar su contraseña y la ubicación de su volumen estándar, entonces su contenido puede ser revelado, pero ** no ** la existencia del volumen oculto dentro. 

Imagínese un maletín con un compartimento secreto. Guarda los archivos que no le importa confiscar o perder en la sección normal de su maletín, y guarda los archivos importantes y privados en el compartimento secreto. El objetivo del compartimiento secreto (especialmente uno bien diseñado) es ocultar su propia existencia y, por lo tanto, los documentos que contiene. 

### 5.1 Cómo crear un volumen oculto 
La creación de a TrueCrypt _Hidden Volume_ es similar a crear TrueCrypt _Standard Volume_: algunos de los paneles, pantallas y ventanas son iguales. 

**Paso 1.** Abra TrueCrypt. 

**Paso 2.** Haga clic en "Crear volumen" para activar _TrueCrypt Volume Creation Wizard_. 

**Paso 3.** Haga clic en "Siguiente" para aceptar el valor predeterminado _Crear un archivo encriptado container_ option. 

**Paso 4.** Compruebe la opción _Hidden TrueCrypt_ volume de la siguiente manera: 
![Image](tool_truecrypt23.png) 

**Paso 5.** Haga clic en "Siguiente " para activar la siguiente pantalla:
![image](tool_truecrypt24.png) 

- _Direct mode_: esta opción te permite crear _Hidden Volume_ dentro de un _Standard Volume_ existente_. 
- Modo normal: esta opción le permite crear un _Volumen estándar_ completamente nuevo en el que almacenar el _Volumen oculto_. 

En este ejemplo, usaremos el _Modo directo_. 

**Nota:** Si preferiría comenzar un nuevo _Tipo estándar_, repita el proceso desde la sección 2.2 Cómo crear un volumen estándar. 

**Paso 6.** Marque la opción _Direct Mode_ y luego haga clic en "Siguiente " para activar _TrueCrypt Creación de volumen - Ventana Ubicación de volumen_. 

**Nota:** Asegúrese de que el _Tipo estándar_ esté desmontado antes de seleccionarlo. 

**Paso 7.** Haga clic en "Seleccionar archivo " para activar lo siguiente pantalla:![image](tool_truecrypt25.png) 

**Paso 8.** Localice el archivo de volumen usando _Seleccione una ventana TrueCrypt Volume_ como se muestra arriba. 

**Paso 9.** Haga clic en "Abrir " para volver al _TrueCrypt Volume Creation Wizard_. 

**Paso 10.** Haga clic en "Siguiente " para activar la pantalla _Enter password_. 

**Paso 11.** Escriba la contraseña que utilizó al crear _Standard Volume_ en el campo de texto _Password_ para ac tiva la siguiente pantalla:
![image](tool_truecrypt26.png) 

**Paso 12.** Haga clic en "Siguiente " después de haber leído el mensaje para activar la pantalla _Hidden Volume Encryptions Options_. 

**Nota:** Deje los ajustes predeterminados de Algoritmo de encriptación y Algoritmo de almohadilla para el Volumen oculto tal como están. 

**Paso 13.** Haga clic en "Siguiente " para activar la siguiente pantalla:
![image](tool_truecrypt27.png) 

Se le pedirá que especifique el tamaño del _Hidden Volume_. 

**Nota:** Tenga en cuenta el tipo de documentos, su cantidad y tamaño que necesitan ser almacenado Deje algo de espacio para el _Tamaño estándar_. Si selecciona el tamaño máximo disponible para _Hidden Volume_, no podrá poner más archivos nuevos en el _Standard Volume_ original. Si su _Standard Volume_ tiene un tamaño de 10 Megabytes (MB) y especifica un _Hidden Volume_ tamaño de 5MB (como se muestra en _figura 6_ anterior), tendrá dos volúmenes (uno oculto y un volumen estándar) de aproximadamente 5MB cada uno. 

Asegúrese de que la información que almacena en _Volumen estándar_ no exceda los 5MB que tiene conjunto. Esto se debe a que el programa TrueCrypt en sí mismo no detecta automáticamente la existencia del _Hidden Volume_ y podría sobrescribirlo accidentalmente. Puede correr el riesgo de perder todos los archivos almacenados en el volumen oculto si excede el tamaño establecido previamente. 

**Paso 14.** Escriba el tamaño de volumen oculto deseado en el cuadro de texto correspondiente como se muestra en la imagen a continuación. 

**Paso 15.** Haga clic en "Siguiente " para activar la ventana _Hidden Volume Password_. 

Ahora debe crear una _different_ contraseña para el volumen oculto de la utilizada para proteger su volumen estándar. Nuevamente, recuerde elegir una contraseña segura. Consulte la **[Guía de la herramienta KeePass](umbrella://lesson/keepassx)** para obtener más información sobre la creación de contraseñas seguras. 

**Sugerencia:** Si prevé ser obligado a revelar los contenidos de sus volúmenes TrueCrypt, luego almacene su contraseña para el volumen estándar en KeePass, y cree una contraseña segura que solo tenga que recordar para el volumen oculto. Esto te ayudará a ocultar tu volumen oculto, ya que no dejarás ningún rastro de su existencia. 

**Paso 16.** Crea una contraseña y escríbela dos veces, y luego haz clic en "Siguiente " para active la siguiente pantalla:
![image](tool_truecrypt28.png) 

Deje las opciones predeterminadas _File System_ y _Cluster_ tal como están. 

**Paso 17.** Mueva el cursor del mouse por la pantalla para aumente la fuerza criptográfica del cifrado y luego haga clic en "Formato " para formatear el volumen oculto. Después de formatear el volumen oculto, aparece la siguiente pantalla:![image](tool_truecrypt29.png) 

**Nota:** _Figure 8_ confirma que ha creado correctamente un volumen oculto y le advierte contra los peligros de sobreescribir archivos en el volumen oculto cuando almacena archivos en el volumen estándar. 

**Paso 18.** Haga clic en "OK " para activar la ventana _Hidden Volume Created_, y luego haga clic en "Exit" y regrese a la consola de TrueCrypt. El volumen oculto ahora se ha creado dentro de su volumen estándar. Ahora puede almacenar documentos en el volumen oculto, que permanecen invisibles incluso para alguien que ha obtenido la contraseña para ese volumen estándar en particular. 

### 5.2 Cómo montar el volumen oculto 
El método para montar o hacer un _Hidden Volume_ accesible para su uso es exactamente el mismo que para un _Standard Volume_; la única diferencia es que usará la contraseña que acaba de crear para _Hidden Volume_. 

To _mount_ o abra _Hidden Volume_, realice los siguientes pasos: 

**Paso 1.** Seleccione una unidad desde la lista (en este ejemplo, unidad _K_):
![imagen](tool_truecrypt30.png) 

**Paso 2.** Haga clic en "Seleccionar archivo ... " para activar el _Seleccione un Volumen TrueCrypt_ ventana. 

**Paso 3.** Navegue y seleccione su archivo _TrueCrypt_ volume (el mismo archivo que para el volumen estándar). 

**Paso 4.** Haga clic en "Abrir " para volver a la consola de TrueCrypt. 

**Paso 5.** Haga clic en "Montar" para activar la pantalla _Enter Password_ for prompt de la siguiente manera: 
![image](tool_truecrypt31.png) 

**Paso 6.** Escriba la contraseña que utilizó para crear el volumen oculto, y luego haga clic en "OK". 

Su volumen oculto ahora está montado (o abierto) de la siguiente manera:
![Image](tool_truecrypt32 .png) 

**Paso 7.** Haga doble clic en la entrada anterior o acceda a ella a través de la ventana _My Computer_. 

### 5.3 Consejos sobre cómo usar el disco oculto Fe ature Securely 
El objetivo de la función de disco oculto es escapar de una situación potencialmente peligrosa al'appearing_ entregar sus archivos encriptados, cuando alguien en una posición de poder exige verlos, sin que en realidad se vea obligado a revelar su información más sensible . Además de proteger sus datos, esto puede permitirle evitar poner en peligro su propia seguridad o exponer a sus colegas y socios. Para que esta técnica sea efectiva, debe crear una situación en la que la persona que exija ver sus archivos esté satisfecha con lo que usted les muestra y lo deja ir. 

Para ello, es posible que desee implementar algunas de las siguientes sugerencias : 
- Coloque algunos documentos confidenciales que no le importe exponer en el volumen estándar. Esta información debe ser lo suficientemente sensible como para que tenga sentido mantenerla en un volumen cifrado. 
- Tenga en cuenta que alguien que exija ver sus archivos puede saber acerca de los volúmenes ocultos. Sin embargo, si usa TrueCrypt correctamente, esta persona no podrá probar que existe su volumen oculto, lo que hará que su negación sea más creíble. 
- Actualice los archivos en el volumen estándar semanalmente. Esto creará la impresión de que realmente está usando esos archivos. 

Siempre que monte un volumen TrueCrypt, puede elegir activar _Protect el volumen oculto contra el daño causado al escribir en la función externa volume_. Una característica muy importante, le permite agregar nuevos archivos 'señuelo' a su volumen estándar sin el riesgo de que borre accidentalmente o sobrescriba los contenidos cifrados de su volumen oculto. 

Como se mencionó anteriormente, excediendo el límite de almacenamiento en su volumen estándar de lo contrario, puede destruir sus archivos ocultos. No habilite la función _Protect hidden volume_ cuando se le obligue a montar un volumen TrueCrypt, porque para hacerlo debe ingresar la contraseña secreta a su volumen oculto y revelará claramente la existencia de ese volumen. Sin embargo, cuando actualice sus archivos señuelo en privado, siempre deberá habilitar esta opción. 

Para usar la función _Protect hidden volume_, realice los siguientes pasos: 

**Paso 1.** Haga clic en "Montar Opciones ... "en el indicador _Enter Password_ que se muestra en la imagen de arriba. Esto activará la ventana _Mount Options_ de la siguiente manera:
![Image](tool_truecrypt33.png) 

**Paso 2.** Verifique _Protect el volumen oculto contra el daño causado por escribir en la opción outer volume_. 

**Paso 3.** Ingrese su contraseña de Hidden Volume, y luego haga clic en "OK ". 

**Paso 4.** Haga clic en "Montar" para montar su volumen estándar. Una vez que lo haya montado correctamente, podrá agregar archivos señuelo sin dañar su volumen oculto. 

**Paso 5.** Haga clic en "Desmontar" para desmontar, o haga que su volumen estándar no esté disponible para su uso , cuando haya terminado de modificar sus contenidos. 

**Recuerde:** Solo necesita hacer esto cuando esté actualizando los archivos en su volumen estándar. Si se ve obligado a revelar su volumen estándar a otra persona, no debe usar la función _Protect hidden volume_. 

### 6. Portable TrueCrypt
![Image](tool_truecrypt34.png) 
Truecrypt conserva sus archivos seguro impidiendo que cualquiera sin la contraseña correcta abra sus documentos y archivos ocultos. Funciona como una caja de seguridad electrónica, que puede usar para bloquear de manera segura sus archivos. 

### 6.1 Diferencias entre las versiones instaladas y portátiles de TrueCrypt 
Dado que las herramientas portátiles no están instaladas en una computadora local, su existencia y uso pueden permanecer sin ser detectados. Sin embargo, tenga en cuenta que su dispositivo externo o dispositivo de memoria USB y herramientas portátiles son solo tan seguros como la computadora que está utilizando y pueden correr el riesgo de estar expuestos a adware, malware, spyware y virus. 

Al igual que muchos de los herramientas de software portátiles documentadas aquí, Portable TrueCrypt le permite usar una herramienta de cifrado de archivos poderosa y simple sin ser detectada. Tener Portable TrueCrypt en un dispositivo extraíble o una memoria USB le permite usarlo desde diferentes estaciones de trabajo. 

Existen muy pocas diferencias entre las versiones instaladas y portátiles de Portable TrueCrypt, la principal es que Portable TrueCrypt no permite el cifrado de todo el disco o el disco del sistema. 

### 6.2 Descarga, extracción y uso de Portable TrueCrypt 
**Nota:** 
La carpeta en la que se extraerá Portable TrueCrypt se debe crear manualmente en el dispositivo extraíble , Memoria USB o disco de la computadora antes del proceso de extracción. 

**Paso 1.** Navegue al destino elegido donde desea extraer el programa Portable TrueCrypt, y luego haga clic con el botón derecho para activar su menú asociado. 

**Paso 2.** Seleccione _New item_ para activar su subcarpeta, y luego seleccione la opción _Folder_ del submenú, como se muestra a continuación:
![image](tool_truecrypt35.png) 

**Paso 3.** Ingrese el nombre de la carpeta.

**Nota:** Puede darle a esta carpeta un aspecto menos obvio nombre para ocultar la existencia del programa Portable TrueCrypt. 

Portable TrueCrypt se puede extraer del mismo archivo que la versión de instalación: 

**Paso 1.** Navegue hasta el archivo de instalación TrueCrypt en su computadora. 

**Paso 2.** Haga doble clic en _TrueCryptSetup7.1.a.exe_; el cuadro de diálogo _Open File - Security Warning_ puede aparecer; si lo hace, haga clic en "Sí" para activar el asistente de instalación de TrueCrypt. 

**Paso 5.** Verifique la opción Extraer para extraer TrueCrypt portable a una unidad extraíble o dispositivo USB como se muestra a continuación:
![image](tool_truecrypt36.png) 

**Paso 6.** Haga clic en "Siguiente" para activar las siguientes dos pantallas:
![image](tool_truecrypt37.png)![image](tool_truecrypt38.png ) 

**Haga clic en** "Aceptar" y "Sí" respectivamente para activar la ventana 

**Opciones de extracción** de la siguiente manera:
![image](tool_truecrypt39.png) 

**Paso 7.** Haga clic en "Examinar" para activar la ventana _Browse for Folders_ de la siguiente manera:
![Image](tool_truecrypt40.png) 

**Paso 8.** 

Navegue a su carpeta de destino ya sea en el disco externo o en el dispositivo de memoria USB, y luego haga clic en "OK ", para regresar a la ventana _Extraction Options_ de la siguiente manera:
![image](tool_truecrypt41.png) 

**Paso 9.** Haga clic en "Extraer" para comenzar a extraer TrueCrypt en su unidad extraíble o memoria USB; unos segundos más tarde, aparecerán las siguientes ventanas:
![image](tool_truecrypt42.png) 

**Paso 10.** Haga clic en "OK" y luego en "Finish " para completar el proceso de instalación. Si la opción "Abrir la ubicación de destino cuando fininshed "está habilitada (como suele ser de forma predeterminada), aparecerá la siguiente pantalla: 

**Paso 11.** Navegue a y luego haga doble clic en _TrueCrypt.exe_ para ejecutar Portable TrueCrypt. 

Por favor, consulte las instrucciones para TrueCrypt común a partir de este punto en adelante, para más información sobre cómo usar TrueCrypt. 

### 6.3 Cómo eliminar todas las huellas de haber extraído Portable TrueCrypt
**Importante:** Después de haber extraído Portable TrueCrypt con éxito a su dispositivo externo / extraíble, debe eliminar el archivo de instalación de su computadora para eliminar aún más rastros de haberlo descargado e instalado. TrueCrypt. 

**Paso 1.** Navega hasta la carpeta en la que se descargó Portable TrueCrypt, y luego haz clic con el botón derecho en _TrueCryptSetup 7.1.a.exe_ archivo de instalación para activar el menú emergente de Windows; luego, seleccione el comando "Eliminar " para moverlo a su Papelera de reciclaje. 

**Paso 2.** Haga doble clic en la Papelera de reciclaje para abrir su ventana asociada, y luego seleccione y elimine el archivo. 

**Nota:** 
Si tiene CCleaner o Eraser instalados, puede usar cualquiera de ellos para eliminar todos los rastros de haber descargado e instalado Portable TrueCrypt. Consulte **[Lección de eliminación segura](umbrella://lesson/eliminación segura)** para obtener más información sobre cómo hacer esto.