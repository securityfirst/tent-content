[Title]: # ()
[Order]: # (0)

# COBIAN BACKUP GUÍA DE HERRAMIENTAS

## Cobian Backup
Realizar los archivos de su computadora

**Lección para leer:** [Copia de seguridad](umbrella://lesson/backing-up)  
**Ubicación de la descarga:** [http://www.cobiansoft.com/cobianbackup.htm](http://www.cobiansoft.com/cobianbackup.htm)  
**Requisitos de la computadora:**
- XP, 2003 , Vista, 2008, Windows 7
- Windows 95, 98 y ME son compatibles con la versión 7 de Cobian.

**Versión utilizada en esta guía:** Cobian 10  
**Licencia:** Freeware  
**Nivel:** Intermedio  
**Tiempo requerido:** 30 minutos

### 1. Cosas que debe saber sobre esta herramienta antes de comenzar

Cobian Backup se utiliza para archivar, (o para crear copia de seguridad) de sus archivos y directorios. Las copias de seguridad se pueden almacenar en otros directorios o unidades en su computadora, otras computadoras en la red de la oficina o en dispositivos extraíbles (CD, DVD y memorias USB). Cobian Backup le permite archivar sus directorios y archivos regularmente. Funciona silenciosamente en segundo plano en su sistema (es decir, en la bandeja del sistema), verifica su programación y ejecuta el proceso de copia de seguridad cuando es necesario. Cobian Backup también puede comprimir y encriptar archivos a medida que genera el archivo de respaldo.

- El uso de Cobian le dará:
- La capacidad de realizar copias de seguridad de todos los documentos, archivos y carpetas.
- La capacidad de comprimir y descomprimir su archivos de respaldo
- La capacidad de encriptar y desencriptar sus archivos archivados

**Instalar Cobian - en resumen**
- Abrir www.cobiansoft.com/cobianbackup.htm
- Haga clic en el enlace "Descargar Cobian Backup" en la página.
- Guarde el instalador, luego búsquelo y haga doble clic en él
- Lea la 'Nota de instalación' a continuación antes de continuar
- Después de instalar con éxito Cobian, puede eliminar el programa de instalación de su computadora.

### 2.0 Cómo instalar Cobian Backup

**Nota de instalación:** Antes de comenzar el proceso de instalación, verifique que tenga las últimas versiones de **Instalador de Microsoft Windows** y **Microsoft.NET Framework**.

Instalar Cobian Backup es un procedimiento relativamente fácil y rápido.

**Paso 1.** Haga doble clic en "cbsetup.exe "; el cuadro de diálogo _Open File - Security Warning_ puede aparecer. Si lo hace, haga clic en "Ejecutar " para activar el color azul claro _Extrayendo la barra de estado de progreso de resource_, seguido unos momentos más tarde por la siguiente pantalla:
![Image](tool_cobian1.png)

**Paso 2.** Haga clic en "Siguiente" para activar el _Lea y acepte la pantalla del acuerdo de licencia_ marque la opción _I accept_ y luego haga clic en "Siguiente" nuevamente para activar la siguiente pantalla:
![Image](tool_cobian2.png)

**Paso 3.** Haga clic en "Siguiente" para activar la siguiente pantalla:
![image](tool_cobian3.png)

**Paso 4.** Compruebe la _Utilice la opción Account_ System local en el panel _Service options_, para que la suya se asemeje a la Figura 3 anterior. Esta opción asegura que Cobian Backup se ejecutará silenciosamente en segundo plano todo el tiempo, para que las copias de seguridad se realicen según lo programado.

**Paso 5.** Haga clic en "Siguiente" para activar el siguiente mensaje:
![image](tool_cobian4.png)

**Paso 6.** Haga clic en "Sí" para activar la siguiente pantalla de instalación, y luego haga clic en "Siguiente" para continuar con el proceso de instalación.

**Paso 7.** Haga clic en "Hecho" para completar el proceso de instalación. Una vez que se haya completado el proceso de instalación, aparecerá el icono de Cobian Backup en la **Bandeja del sistema de Windows**.

### 2.1 Cómo hacer una copia de seguridad de sus directorios y archivos

En esta sección aprenderá cómo realice una copia de seguridad simple o archivo de archivos y/o carpetas especificados. Cobian Backup usa una _backup task_ que se puede configurar para incluir un grupo específico de archivos y/o carpetas. Se puede configurar una tarea de copia de seguridad para que se ejecute en un día y una hora especificados.

Para crear una nueva tarea de copia de seguridad, realice el siguiente paso:

**Paso 1.** Haga clic en "Programar" para crear un nueva tarea de copia de seguridad y active la ventana _New task_ de la siguiente manera:
![image](tool_cobian5.png)

La barra lateral izquierda enumera varias pestañas y sus pantallas asociadas, que se utilizan para configurar diferentes opciones de copia de seguridad y parámetros, son se muestra en el panel a la derecha. Todas las opciones en la pestaña _General_ se describen a continuación:

### 2.1.1 Descripciones de las Opciones

_Task Name:_ Este campo de texto _Task Name_ le permite ingresar un nombre para la tarea de respaldo. Use un nombre que identifique la naturaleza de la copia de seguridad. Por ejemplo, si la copia de seguridad va a contener archivos de video, puede ponerle el nombre _Video Backup_.

_Disabled:_ Esta opción _debe_ dejarse sin marcar.
Advertencia: la habilitación de la opción _Disable_ anulará el resto de las opciones y evitará que se ejecute la tarea de copia de seguridad.

_Include Subdirectories:_ Esta opción le permite incluir todos los subdirectorios/carpetas dentro de un directorio/carpeta seleccionado para la tarea de copia de seguridad . Este es un método eficiente para realizar copias de seguridad de una gran cantidad de carpetas y/o archivos. Como ejemplo, si selecciona la carpeta _My Documents_ y marca esta opción, todos los archivos y carpetas en _My Documents_ se incluirán en la tarea de copia de seguridad.

_Crear copias de seguridad separadas usando timestamps:_ Esta opción le permite especificar la fecha y el tiempo de la tarea de respaldo se incluirá automáticamente en el nombre de la carpeta que contiene su archivo de respaldo. Esta es una buena idea porque significa que podrá identificar fácilmente cuándo se realizó la copia de seguridad.
_Utilice la lógica de atributo de archivo:_ Esta opción solo es relevante cuando elige realizar una copia de seguridad incremental o diferencial (consulte a continuación). Los atributos de archivo contienen información sobre el archivo.

**Nota:** La siguiente opción solo está disponible para las versiones del sistema operativo Windows más recientes que _y_, incluido Windows XP.

_Use Volume Shadow Copy:_ Esta opción le permite realizar copias de seguridad archivos que están bloqueados
Cobian Backup verifica esta información para determinar si ha habido un cambio en el archivo fuente desde la última vez que se realizó una copia de seguridad. Si luego ejecuta una copia de seguridad _Differential_ o _Incremental_, el archivo se actualizará.

**Nota:** Solo podrá ejecutar una copia de seguridad completa o 'falsa' si _hacia esta opción_ (la opción de copia de seguridad ficticia se explica a continuación).

### 2.1.2 Descripciones del tipo de copia de seguridad

_Full:_ Esta opción significa que cada archivo en la ubicación de origen se copiará en el directorio de la copia de seguridad. Si ha habilitado _Crear copias de seguridad separadas usando la opción timestamp_, tendrá varias copias de la misma fuente (identificadas por la fecha y hora de la copia de seguridad en el título de la carpeta). De lo contrario, Cobian Backup sobrescribirá la versión anterior (si corresponde).

_Incremental:_ Esta opción significa que el programa verificará si los archivos seleccionados para la copia de seguridad se han modificado desde que se realizó la última copia de seguridad. Si no ha habido cambios, se omitirá durante el proceso de copia de seguridad, lo que ahorrará tiempo de respaldo. La opción _Use file attribute logic_ necesita ser verificada para realizar esta copia de seguridad.

_Differential:_ El programa verificará si la fuente ha sido cambiada desde la última copia de seguridad **completa**. Si no es necesario copiar ese archivo, se saltará y se ahorrará tiempo de respaldo. Si antes ha ejecutado una copia de seguridad completa en el mismo conjunto de archivos, puede continuar realizando una copia de seguridad utilizando el método Diferencial.

_Pleta obsoleta:_ Puede usar esta opción para que su computadora se ejecute o cierre programas. en ciertos momentos. Esta es una opción más avanzada que no es realmente relevante para nuestro procedimiento de respaldo básico.

**Paso 2.** Haga clic en "Aceptar" para confirmar sus opciones de búsqueda y parámetros para su tarea de respaldo.

### 2.2 Cómo crear un archivo de respaldo

Para comenzar a crear un archivo de respaldo, realice los siguientes pasos:

**Paso 1.** Haga clic en "Archivos" en la barra lateral izquierda de la _Nueva tarea_ ventana para mostrar una _blank_ versión de la siguiente pantalla:
![image](tool_cobian6.png)

**Paso 2.** Seleccione los archivos que desea hacer una copia de seguridad. (En _Figura 3_ arriba, la carpeta _My Documents_ está seleccionada.)

**Paso 3.** Haga clic en "Agregar" en el panel _Source_ para activar el menú _Directory_.

**Paso 4.** Seleccione _Directory_ si desea realizar una copia de seguridad de un directorio completo, y _Files_ para hacer una copia de seguridad de los archivos individuales. Para especificar archivos o directorios individuales de los que se realizará una copia de seguridad, seleccione _Manualmente_ y escriba la ruta o el directorio del archivo para su copia de seguridad.

**Nota:** Puede agregar tantos archivos o directorios como desee. Si desea hacer una copia de seguridad de los archivos actualmente en su servidor FTP, elija la opción del sitio FTP (necesitará los detalles de inicio de sesión del servidor).

Cuando haya seleccionado los archivos y/o carpetas, aparecerán en el _Source_ area. Como se puede ver en _Figura 3_ anterior, la carpeta _My Documents_ se muestra allí, lo que significa que esta carpeta se incluirá ahora en la tarea de copia de seguridad.

El panel _Destination_ especifica dónde se almacenará la copia de seguridad.

**Paso 5.** Haga clic en "Agregar" en el panel _Destination_ para activar el menú Directorio.

**Paso 6.** Seleccione _Directory_ para abrir una ventana del navegador donde seleccione la carpeta de destino para su archivo de respaldo.

**Nota:** Si desea crear varias versiones del archivo de copia de seguridad, puede especificar varias carpetas aquí. Si seleccionó la opción _Manually_, debe escribir la ruta completa a la carpeta donde desea guardar la copia de seguridad. Para usar un servidor de Internet remoto para almacenar su archivo, seleccione la opción del sitio FTP (deberá tener los datos de inicio de sesión del servidor apropiados).

La pantalla ahora debería parecerse al ejemplo anterior con archivos y/o carpetas en el área de origen y carpetas en el área de destino. Sin embargo, ¡no hagas clic en _OK_ todavía! Aún necesita establecer un cronograma para su copia de seguridad.

### 2.3 Cómo programar su tarea de respaldo

Para que su copia de seguridad automática funcione, debe completar la sección _Esquema_. Esta sección le permite especificar cuándo desea que se realice la copia de seguridad.
Para configurar las opciones de programación, realice los siguientes pasos:

**Paso 1.** Seleccione "Programar" desde la barra lateral izquierda, para activar el siguiente panel:
![image](tool_cobian7.png )

Las opciones _Esquema tipo_ se enumeran en el menú desplegable y se describen a continuación:

_Una vez:_ La copia de seguridad se realizará una sola vez en la fecha y hora especificadas en el área _Fecha/Hora_.

_Daily:_ La copia de seguridad se realizará todos los días a la hora especificada en el área _Date/Time_.

_Weekly:_ La copia de seguridad se realizará los días de la semana seleccionada. En el ejemplo anterior, la copia de seguridad se realizará los viernes. También puede seleccionar otros días. La copia de seguridad se realizará en todos los días seleccionados en el momento especificado en el área _Fecha/Hora_.

_Mesimo:_ La copia de seguridad se realizará los días ingresados en el cuadro de días del mes a la hora especificada en _Fecha/Time_ area.

_Yearly:_ La copia de seguridad se realizará los días ingresados en el cuadro de días del mes, durante el mes especificado, y en el momento especificado en el área _Date/Time_.

_Timer:_ The la copia de seguridad se realizará repetidamente a los intervalos especificados en el cuadro de texto del Temporizador en el área _Fecha/Hora_.

_Manualmente:_ Deberá ejecutar la copia de seguridad usted mismo desde la ventana principal del programa.

**Paso 2.** Haga clic en "Aceptar" para confirmar las opciones y configuraciones para la programación de la copia de seguridad de la siguiente manera:
![Image](tool_cobian8.png)

Una vez que haya decidido hacer una copia de seguridad, habrá completado el último paso. La copia de seguridad ahora se ejecutará en las carpetas especificadas de acuerdo con la programación que haya elegido.

### 3.0 Cómo comprimir su archivo de respaldo

**Paso 1.** Cree una tarea de respaldo como se documenta en la sección 2.3, que contiene los archivos de respaldo que desea archivar.

**Paso 2.** Seleccione "Archivar" desde la barra lateral izquierda para activar la pantalla _New task_ de la siguiente manera:
![Image](tool_cobian9. png)

El panel **Compresión** se usa para especificar el método para comprimir su copia de seguridad.

**Nota:** La compresión se usa para reducir la cantidad de espacio para el almacenamiento de archivos. Si tiene un grupo de archivos antiguos que usa solo ocasionalmente, pero aún desea conservarlos, tendría sentido almacenarlos en un formato en el que ocupen el menor espacio posible. La compresión funciona eliminando una gran cantidad de códigos innecesarios de sus documentos, mientras deja intacta la información importante. La compresión no daña sus datos originales. Los archivos no son visibles cuando se comprimen. El proceso debe invertirse y sus archivos deben 'descomprimirse' cuando desee volver a ver los archivos.

Las tres subopciones de la lista desplegable _Compresión tipo_ son:

_No Compresión:_ Esta opción no funciona cualquier compresión, como era de esperar.

_Compresión de compresión:_ Esta opción es la técnica de compresión estándar para sistemas **Windows** y la más conveniente. Los archivos una vez creados se pueden abrir con las herramientas estándar de Windows (o puede descargar el programa [ZipGenius](http://www.zipgenius.it/) para acceder a ellos).

Seleccionar un tipo de compresión enumerado automáticamente habilita las _Opciones de división_ sección, y su lista desplegable correspondiente.

Las _Opciones de división_ se aplican al almacenamiento en medios extraíbles, por ejemplo, CD, DVD, disquetes y memorias USB. Las distintas opciones de división subdividirán el archivo en tamaños que se ajustarán a su dispositivo de almacenamiento preferido.

**Ejemplo:** Digamos que está archivando una gran cantidad de archivos y desea grabarlos en un CD. Sin embargo, su tamaño de archivo resulta ser más grande que 700 MB (el tamaño de un CD). La función de división dividirá el archivo en partes menores o iguales a 700 MB, que luego puede grabar en sus CD. Si planea hacer una copia de seguridad en el disco duro de su computadora, o los archivos que desea respaldar son más pequeños que el dispositivo en el que planea almacenarlos, puede omitir esta sección.

Las siguientes opciones están disponibles para usted cuando haces clic en la lista desplegable _Split options_. Su elección dependerá del tipo de dispositivo de almacenamiento extraíble disponible para usted.
![Image](tool_cobian10.png)

- 3,5": Disquete. Esta opción es lo suficientemente grande como para realizar una copia de seguridad de un pequeña cantidad de documentos
- Zip: Zip Disk (verifique la capacidad del que está utilizando). Necesitará una unidad Zip especial en su computadora y los discos a medida
-CD-R-CD: (verifique la capacidad del que está usando). Necesitará un escritor de CD en su computadora y un programa de grabación de CD (consulte la versión [DeepBurner Free](http://www.deepburner.com/) u otras [herramientas de grabación en disco](http://www.thefreecountry.com/utilities/dvdcdburning.shtml)).
- DVD: Disco DVD (verifique la capacidad del que está usando). Necesitará un DVD Writer en su computadora y un DVD. Programa de escritura (vea la versión [DeepBurner Free](http://www.deepburner.com/) u otras [herramientas de grabación de disco](http://www.thefreecountry.com/utilities/dvdcdburning.shtml)).

Si está realizando una copia de seguridad en varias tarjetas de memoria USB, es posible que desee t o establecer un tamaño personalizado.

Para ello, realice los siguientes pasos:

**Paso 1. Seleccione** la opción _Custom size_ (bytes), luego escriba el tamaño del archivo en bytes en el texto campo.

Para darle una idea de los tamaños
- 1KB (kilobyte) = 1024 bytes, un documento de texto de una página hecho en Open Office es aproximadamente 20kb
- 1MB (megabyte) = 1024 KB - una foto tomada en una cámara digital es generalmente entre 1 - 3 MB
- 1 GB (gigabyte) = 1024 MB - aproximadamente media hora de una película de calidad DVD

**Nota:** Cuando elija un tamaño personalizado para dividir su copia de seguridad un disco CD o DVD, Cobian Backup no copiará la copia de seguridad automáticamente en su dispositivo extraíble. Más bien, creará su archivo en esos archivos en la computadora y tendrá que grabarlos en el disco de CD o DVD usted mismo.

_Password protected_ Esta opción le permite ingresar una contraseña para proteger el archivo. Simplemente escriba, luego vuelva a escribir una contraseña en los dos cuadros provistos. Cuando intente descomprimir el archivo, se le pedirá la contraseña antes de que comience la tarea.

**Nota:** Si desea proteger su archivo, debe pensar en utilizar otro método que no sea una contraseña. Cobian Backup te permite encriptar tu archivo. Esto se trata a continuación.

_Comment:_ Esta opción le permite escribir algo descriptivo sobre el archivo, pero no es un requisito.

### 3.1 Cómo descomprimir el archivo de respaldo

Para descomprimir su copia de seguridad , realice los siguientes pasos:

**Paso 1.** *Seleccione > Herramientas > Descompresor.*

La ventana del descompresor aparece de la siguiente manera:
![image](tool_cobian11.png)

**Paso 2.** Haga clic en el ícono de abrir archivo para abrir una ventana de exploración para permitirle seleccionar el archivo que desea descomprimir.

**Paso 3.** Seleccione el archivo (_.zip_ o _ .7x_ file) y luego haga clic en "OK ".

**Paso 4.** Seleccione un directorio en el cual desempaquetará (salida) el archivo archivado.

**Paso 5.** Haga clic en el icono de compresión para abrir otra ventana que le permite elegir la carpeta en la que desea descomprimir el archivo.

**Paso 6.** Seleccione una carpeta, y luego haga clic en "OK".

Use Explorador de Windows para ver los archivos que van a esa carpeta.

### 4.0 Acerca de Encriptación

La encriptación puede ser una necesidad para aquellos que deseen o mantener su copia de seguridad segura del acceso no autorizado. El cifrado es el proceso de codificación o codificación de datos de tal manera que parece ininteligible para cualquiera que no tenga la clave específica necesaria para decodificar el mensaje. Para obtener más información sobre encriptación, lea la lección [Protecting Files](umbrella://lesson/protect-files).

### 4.1 Cómo cifrar su archivo de respaldo

El panel _Strong encryption_ se usa para especificar el método de encriptación que se utilizará.

**Paso 1.** Haga clic en el cuadro desplegable _Encryption_ type para activar su lista de diferentes métodos de encriptación.

Para simplificar las cosas, le recomendamos que elija entre los métodos _Blowfish_ o _Rijndael_ (128 bits). Esto proporcionará una excelente seguridad para su archivo y le permitirá acceder a los datos cifrados con una contraseña elegida.

**Paso 2.** Seleccione el tipo _Encryption_ que desea usar.

**Nota:** _Rijndael_ y _Blowfish_ ofrecen aproximadamente el mismo nivel de seguridad. _DES_ es más débil pero el proceso de encriptación es más rápido.

**Paso 3.** Escriba y vuelva a escribir la contraseña en los dos cuadros provistos.

La fortaleza de la contraseña se indica mediante la barra marcada 'Frase de contraseña' calidad. Cuanto más se mueve la barra hacia la derecha, más fuerte es la frase de contraseña. Consulte la **[Lección Contraseñas](umbrella://lesson/passwords)** para obtener información sobre cómo crear y almacenar contraseñas seguras.

**Paso 4.** Haga clic en "Aceptar".

### 4.2 Cómo descifrar el archivo de respaldo

Descifrar el archivo de respaldo es fácil y rápido. Para descifrar su archivo de copia de seguridad, realice los siguientes pasos:

**Paso 1.** *Seleccione > Herramientas > Descifrador y Teclas:*

_Esto activará la ventana Descifrador y Teclas de la siguiente manera:_
![image](tool_cobian12.png)

**Paso 2.** Haga clic en "Seleccionar" para seleccionar el archivo que desea descifrar.

**Paso 3.** Haga clic en "Destino" para seleccionar la carpeta en la que almacenar el archivo descifrado.

**Paso 4.** Seleccione el mismo tipo de cifrado que seleccionó anteriormente, en la sección 4.1 Cómo cifrar su archivo de respaldo, en la lista desplegable _Métodos_ .

**Paso 4. Seleccione** el método de encriptación apropiado (el que usó para encriptar su archivo de respaldo).

**Paso 5.** Escriba su frase de contraseña en los campos de texto _Passphrase_.

**Paso 6.** Haga clic en "Descifrar!"

Los archivos se descifrarán a la ubicación que usted especificó. Si los archivos también se comprimieron, tendrá que descomprimirlos como se describe en la sección 3.1 Cómo descomprimir su copia de seguridad.
