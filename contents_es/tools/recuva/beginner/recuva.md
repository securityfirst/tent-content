[Title]: # ()
[Order]: # (0)

## GUÍA DE HERRAMIENTAS RECUVA

Recuperación de datos y eliminación segura

**Lección para leer:** [Copia de seguridad](umbrella://lesson/backing-up)  
**Ubicación de descarga:** [http://www.piriform.com/recuva/builds](http://www.piriform.com/recuva/builds)  
**Requisitos informáticos:** Cualquier versión de Windows  
**Version usado en esta guía:** Recuva 1.3  
**Licencia:** Freeware  
**Nivel:** Intermedio  
**Tiempo requerido:** 20 minutos.  

**El uso de Recuva le dará:**
- La capacidad de realizar diferentes técnicas de escaneo 
- La capacidad de recuperar archivos previamente eliminados en su computadora, incluidos correos electrónicos, imágenes y videos 
- La capacidad de eliminar de forma segura información privada o confidencial 

**Los usuarios de Mac OS podrían usar [TestDisk y PhotoRec](www.cgsecurity.org/), como alternativa, que también son compatibles con Microsoft Windows y GNU Linux.**

### 1.1 Antes de comenzar

En situaciones donde archivos privados o confidenciales pueden haber sido borrados por error, Recuva puede ayudarlo a escanear y restaurar algunos de ellos. Como se explica en la **[lección de eliminación](umbrella://lesson/safely-deleting)**, se borró un archivo con la función de eliminación del sistema operativo estándar de Windows, incluso después del reciclaje. Bin se ha vaciado, puede que aún exista en la computadora.

Sin embargo, existen circunstancias bajo las cuales Recuva no puede recuperar información. Si ha eliminado o borrado permanentemente cualquier archivo temporal ejecutando CCleaner con la opción de eliminación segura de archivos (Más lenta) habilitada, esos archivos son prácticamente irrecuperables. Recuva no puede recuperar archivos después de que se hayan utilizado programas como CCleaner o Eraser para borrar el espacio libre en el disco o si Windows ya sobrescribió un espacio previamente ocupado. Recuva tampoco puede recuperar documentos y archivos dañados.

**Recuva también se puede utilizar para sobrescribir de manera segura sus datos privados o confidenciales.**

### Cómo instalar Recuva

### 2.0 Cómo para instalar Recuva

**Paso 1.** Haga doble clic en "rcsetup138.exe"; el cuadro de diálogo _Abrir archivo_ Advertencia de seguridad puede aparecer. Si lo hace, haga clic en "Ejecutar" para activar el cuadro 1de idioma.

**Paso 2.** Haga clic en "Aceptar" para activar la pantalla Bienvenido al _Asistente de configuración de Recuva._

**Paso 3.** Haga clic en "Siguiente" para activar la pantalla _Acuerdo de licencia . Lea el _Acuerdo de licencia antes_ de continuar con el resto del proceso de instalación.

**Paso 4.** Haga clic en "Acepto" para activar la pantalla de ubicación _Elegir instalar_.

**Paso 5.** Haga clic en "Siguiente" para activar la pantalla _Instalar opciones_.

Nota: aparece la pantalla _Instalar opciones con la_ Instalar Yahoo opcional ! barra de herramientas opción habilitada. No _no instalo el Yahoo! barra de herramientas_, que puede comprometer su privacidad y seguridad en Internet.

**Paso 6.** Compruebe la Instale Yahoo! opcional barra de herramientas para desactivarlo como se muestra a continuación: 
![image](tool_recuva1.png) 

**Paso 7.** Haga clic en "Instalar" para comenzar a instalar Recuva. Esto activará la barra de progreso de la instalación que desaparecerá después de que la instalación se haya completado en unos minutos.

**Paso 8.** Haga clic en "Fin" para completar la instalación de Recuva.

_Ahora que ha instalado Recuva correctamente, está listo para comenzar a recuperar y / o sobrescribir información confidencial y privada._

### Cómo realizar diferentes escaneos usando Recuva

### 3.0 antes de comenzar

En esta sección, aprenderá cómo realizar diferentes tipos de escaneos, y se le presentará a las pestañas _General_ y _Acciones_ en la pantalla _Opciones_. 

**Nota:** Un escaneo simplemente recuperará y mostrará los archivos que son potencialmente recuperables. Los procedimientos de recuperación reales se discuten en la siguiente sección.

### 3.1 Cómo realizar un escaneo con el Asistente de Recuva

El Asistente de Recuva se recomienda en situaciones donde ni el nombre completo ni parcial del archivo que desea recuperar se conoce. También se recomienda si es la primera vez que usa Recuva. El Asistente de Recuva le permite configurar los parámetros de escaneo permitiéndole especificar el tipo de archivo y / o desde donde se borró el archivo.

Para comenzar a escanear los archivos eliminados, realice lo siguiente pasos:

**Paso 1.** Haga clic en el icono Recuva o seleccione _Inicio > Programas > Recuva > Recuva_ para iniciar el programa y active la siguiente pantalla: 
![image](tool_recuva2.png)

Sugerencia: si conoce el nombre exacto o parcial de un archivo que desea recuperar, haga clic en "Cancelar" ir a la interfaz de usuario principal de _Piriform Recuva_ y luego seguir los pasos de la sección 3.2 Cómo realizar un escaneo sin usar el Asistente de Recuva.

**Paso 2.** Haga clic en "Siguiente" para activar la siguiente pantalla: 
![image](tool_recuva3.png)

El tipo de archivo de Asistente de Recuva muestra una lista de diferentes tipos de archivos y describe qué archivos pueden recuperarse cuando cada opción está habilitada.

**Paso 3.** Compruebe la opción _Otro_ , y luego haga clic en "Siguiente" para activar la siguiente pantalla: 
![image](tool_recuva4.png) 

**Nota:** la configuración predeterminada para la pantalla _Recuva Wizard Ubicación del archivo es la opción_ No estoy seguro. Esta opción extenderá el escaneo a todas las unidades así como a los medios extraíbles, excepto CD, DVD y medios ópticos. Por lo tanto, puede requerir más tiempo para generar resultados.

Los archivos se eliminan con mayor frecuencia de la Papelera de reciclaje en los sistemas operativos Windows, para minimizar la posibilidad de eliminar accidentalmente información privada o confidencial.

**Paso 4.** Compruebe la opción En la papelera de reciclaje como se muestra arriba, y luego haga clic en "Siguiente" para activar la siguiente pantalla: 
![image](tool_recuva5.png)

**Nota:** para este ejercicio, no habilite la opción Deep Scan. Esta técnica de escaneo se analizará en la sección 3.3 Cómo realizar un escaneo profundo.

**Paso 5.** Haga clic en "Comenzar" para comenzar a recuperar los archivos eliminados.

Durante el proceso de recuperación de archivos, aparecen dos barras de estado de progreso en rápida sucesión. La barra de progreso _Escaneo de la unidad para archivos eliminados_ enumera los archivos eliminados. Los grupos de barra de progreso_ Analizar el contenido del archivo_ clasifican los archivos eliminados en tipos de archivos y el grado de capacidad de recuperación. También muestran la duración de los procesos de análisis y análisis. Su interfaz de usuario principal de _Piriform Recuva_ puede parecerse a la siguiente pantalla: 
![image](tool_revua6.png)

La interfaz de usuario Piriform Recuva enumera información sobre cada archivo eliminado, organizado en seis columnas. Cada columna se describe de la siguiente manera:

**Nombre de archivo:** Muestra el nombre y la extensión de archivo del archivo eliminado. Haga clic en el título _Nombre de archivo para organizar los archivos eliminados en orden alfabético._

**Ruta:** Esto muestra dónde se encontró el archivo eliminado. Dado que la opción _En la Papelera de reciclaje_ se habilitó en este ejemplo, la ruta del archivo es _C:\RECYCLER_ para todos los archivos eliminados. Haga clic en el título _Ruta_ para ver todos los archivos enumerados en un directorio o ruta de archivo en particular.

**Última modificación:** Muestra la última vez que se realizó el archivo modificado antes de su eliminación, y puede ser útil para ayudar a identificar el archivo que desea recuperar. Haga clic en _Última modificación_ para mostrar los archivos eliminados según el formato más antiguo o más reciente.

**Tamaño:** Esto muestra el tamaño del archivo. Haga clic en Tamaño para mostrar los archivos eliminados comenzando con el archivo eliminado más grande o más pequeño.

**Estado:** Esto muestra hasta qué punto es recuperable el archivo, y corresponde a los iconos de estado del archivo que se describen a continuación. Haga clic enEstado para ordenar los archivos eliminados en las tres categorías básicas y enumerarlos de Excelente aIncumplible.

**Comentario:** Esto muestra por qué un archivo dado puede o no ser recuperable, y el grado en que se sobrescribió un archivo eliminado en la Tabla principal de archivos de Windows. Haga clic en _Comentario_ para ver en qué medida se sobrescribió un archivo o grupo de archivos.

Cada archivo está asociado a un icono de estado de color que indica el grado en que cada archivo puede recuperarse con éxito:

La siguiente lista describe cada icono de estado:

- Verde: las posibilidades de una recuperación completa son excelentes. 
- Naranja: las posibilidades de recuperación son aceptables. 
- Rojo: las posibilidades de recuperación son poco probables.

### 3.2 Cómo realizar un escaneo sin utilizar el Asistente de Recuva

Para acceder directamente a la interfaz de usuario principal de Recuva, (es decir, no usar el _Recuva Wizard_), realice los siguientes pasos:

**Paso 1.** Haga clic en el icono Recuva o seleccione _Inicio > Programas > Recuva > Recuva._

**Paso 2.** Compruebe la opción No mostrar este asistente al inicio , luego haga clic en "Cancelar" para activar la siguiente pantalla: 
![image](tool_recuva7.png)

La interfaz de usuario principal de Piriform Recuva está dividida en el panel de resultados a la izquierda y el Obtenga una vista previa de las pestañas, Información y Encabezado para ordenar y ver información sobre un archivo eliminado específico. Le permite establecer ciertas opciones de escaneo, similares a las del Asistente de Recuva.

**Paso 3.** Haga clic para activar la lista desplegable y seleccione el disco a escanear; el _Disco local (C:)_ es el predeterminado y se usa en este ejemplo de la siguiente manera: 
![image](tool_recuva8.png) 

El _Nombre de archivo_ o _ruta_ lista desplegable que le permite especificar el tipo de archivo que está buscando, y se corresponde libremente con la pantalla _Recuva Wizard File type_. 
![image](tool_recuva9.png) 

La función Nombre de archivo o ruta es una combinación de un cuadro de texto y una lista desplegable. Tiene dos usos principales: permitirle buscar directamente un archivo específico y / o ordenar a través de una lista de archivos eliminados, de acuerdo con el tipo de archivo.

Alternativamente, el _Nombre de archivo_ o _ruta_ se puede utilizar para buscar archivos de un tipo específico, o para ordenar a través de una lista general de archivos eliminados en el panel de resultados.

Para comenzar a buscar un archivo del que se conoce todo o parte del nombre, realice los siguientes pasos:

**Paso 1.** Escriba el nombre o el nombre parcial de un archivo que desea recuperar como sigue (en este ejemplo, se está escaneando el archivo _triangle.png_): 
![image](tool_recuva10.png)

**Consejo:** Haga clic en X para reiniciar _Nombre de archivo y ruta_ (que aparecen atenuados).

**Paso 2.** Haga clic en "Explorar" para comenzar a buscar sus archivos borrados; poco después, aparecerá una pantalla similar a la siguiente: 
![image](tool_recuva11.png) 

### 3.3 Cómo realizar una exploración profunda usando Recuva

El Enable Deep La opción Escanear le permite realizar un escaneo más completo; naturalmente, una exploración profunda lleva más tiempo, según la velocidad de su computadora y la cantidad de archivos que tenga. Esta opción puede resultar útil si su exploración inicial no muestra los archivos que le gustaría recuperar. Aunque un escaneo profundo puede incluso tomar horas dependiendo de la cantidad de datos almacenados en su computadora, puede mejorar sus posibilidades de recuperar los archivos que necesita.

La opción Recuva Deep Scan se puede habilitar al marcar la opción Habilitar exploración profunda en el Asistente de Recuva.

**Paso 1.** Hacer clic "Opciones" para activar la pantalla Opciones, luego haga clic en la pestaña _Acciones_ de la siguiente manera: 
![image](tool_recuva12.png) 

**Paso 2** Compruebe la opción Exploración profunda (aumenta el tiempo de exploración), luego haga clic en "Aceptar".

**Paso 3.** Haga clic en "Explorar" para comenzar a buscar archivos eliminados usando la opción _Exploración profunda_. Como se mencionó anteriormente, un escaneo profundo puede tomar unas horas, dependiendo del tamaño del disco duro y la velocidad de la computadora: 
![image](tool_recuva13.png)

### 3.4 Una Introducción a la Pantalla de Opciones

En esta sección, aprenderá a usar las diferentes configuraciones para recuperar y sobrescribir su información confidencial o privada en la pantalla Opciones. Para configurar estos ajustes, realice los siguientes pasos:

**Paso 1:** Haga clic en "Opciones" para activar la siguiente pantalla: 
![image](tool_recuva14.png) 

La pantalla Opciones se divide en General, Acciones y Acerca de pestañas.

La pestaña General le permite definir una cantidad de configuraciones importantes, que incluyen Idioma (Recuva admite 37 idiomas), Modo de visualización y deshabilitar o habilitar el Asistente de Recuva. 
![image](tool_recuva15.png) 

_The View Mode_ le permite seleccionar cómo le gustaría ver los archivos eliminados, y también se puede habilitar cada vez que haga clic derecho en un archivo en el _Piriform Recuva_.

**Lista:** Esta opción le permite ver los archivos eliminados en una lista 
**Árbol:** Esta opción le permite ver la ruta del directorio de los archivos eliminados en forma de un árbol expandible. 
**Miniaturas:** Esta opción le permite ver los archivos eliminados como gráficos o imágenes siempre que sea posible.

Lo más importante es quizás, la sección Avanzado de La pestaña General le permite establecer el número de veces que sus datos pueden ser sobrescritos por datos aleatorios para protegerlos de la recuperación por parte de terceros hostiles o malintencionados.

La sobrescritura segura lista desplegable muestra cuatro opciones para sobrescribir su información privada. Su modo predeterminado es Sobrescribir simple (1 pase). Un pase se refiere a la cantidad de veces que su documento, archivo o carpeta se sobrescribirá con datos aleatorios para volverlo completamente ilegible.

**Paso 2:** Seleccione el _DOD 5220.22_ M (3 pasos) opción de la siguiente manera: 
![image](tool_recuva16.png)

Una sola pasada puede resultar bastante efectiva para sobrescribir un documento, archivo o carpeta; sin embargo, hay partes con los recursos y las habilidades para recuperar una sobrescritura segura relativamente ligera. Tres pasos es un sólido equilibrio entre el tiempo requerido para realizar una sobrescritura segura y la capacidad de recuperar ese documento, archivo o carpeta.

**Paso 3.** 
Haga clic en "Aceptar" para guardar las opciones de configuración de la pestaña _General_. 
![image](tool_recuva17.png)

**Mostrar los archivos encontrados en los directorios ocultos del sistema:** Esta opción le permite visualizar archivos en directorios ocultos del sistema.

**Mostrar archivos de cero bytes:** Esta opción le permite mostrar archivos que tienen poco o ningún contenido, y que son básicamente irrecuperables. Mostrar archivos borrados de forma segura: esta opción le permite visualizar archivos que se han eliminado de forma segura en el panel de resultados.

**Nota:** Si ya usó CCleaner o un programa similar, cambia el nombre de archivo a ZZZZZZZ.ZZZ cuando borra de manera segura un archivo, por razones de seguridad.

**Exploración profunda:** Esta opción le permite escanear todo el disco en busca del documento o archivo eliminado; si los escaneos anteriores han demostrado ser ineficaces para localizar su archivo, el escaneo profundo puede resultar útil. Sin embargo, requiere más tiempo. Consulte la sección 3.3 Cómo realizar un escaneo profundo usando Recuva.

**Buscar archivos no eliminados (para recuperación de discos dañados o reformateados):** Esta opción le permite intentar recuperar archivos de discos que pueden haber sufrido daños físicos o daños relacionados con el software. 

La pestaña _Acerca de_ muestra información de la versión, así como enlaces al sitio web de Piriform.

Ahora que tiene más confianza en realizar diferentes escaneos y está familiarizado con la configuración en el Las pestañas General y Acciones en la pantalla Opciones, usted está listo para aprender cómo recuperar realmente y / o sobrescribir de forma segura su información privada o confidencial.

### Cómo recuperar y sobrescribir de manera segura los archivos mediante Recuva

### 4.0 Antes de comenzar

En esta sección, aprenderá cómo recuperar un archivo eliminado previamente, y cómo sobrescribir de forma segura cualquier información privada o confidencial.

Recuva le permite crear una nueva carpeta para almacenar sus archivos recuperados. Aunque Recuva le permite usar carpetas existentes, por razones de seguridad, le recomendamos que copie los archivos recuperados en un dispositivo extraíble, como una unidad de copia de seguridad o una memoria USB.

**Importante:** Aunque Recuva hace un excelente trabajo al sobrescribir información de forma segura, puede dejar un marcador de archivo que indique la existencia de dicho archivo. Para proteger su privacidad y seguridad, tiene sentido guardar cualquier información importante, privada o confidencial en un dispositivo extraíble, y no en la ubicación o ruta original.**

### 4.1 Cómo recuperar un archivo eliminado

Para comenzar a recuperar un archivo eliminado, realice los siguientes pasos:

**Paso 1. Conecte su disco extraíble o una memoria USB a su computadora.**

**Paso 2.** Marque la casilla de verificación junto al archivo que desea recuperar para habilitar el botón "Recuperar..." o haga doble clic en ese archivo para verificar y resaltar ese archivo.

**Paso 3.** Haga clic en "¿Recuperar?" para activar la pantalla Buscar carpeta.

**Paso 4.** Seleccione un destino y luego haga clic en? Crear nueva carpeta? para crear su carpeta de recuperación como se muestra a continuación. 
![image](tool_recuva18.png)

**Nota:** En este ejemplo, la carpeta para almacenar sus documentos y archivos recuperados ha sido dada una etiqueta obvia. Sin embargo, teniendo en cuenta su privacidad y seguridad digital, le recomendamos que tenga más cuidado al etiquetar su propia carpeta.

**Paso 5.** Haga clic en "Sí" para comenzar el proceso de recuperación de archivos; Aparecerá una pantalla de estado de progreso de la siguiente manera: 
![image](tool_recuva19.png)

Una vez recuperados los archivos, aparecerá una confirmación similar a la siguiente pantalla: 
![image](tool_recuva20.png)

Ahora que se siente cómodo recuperando un archivo previamente borrado, está listo para aprender a usar el menú emergente para realizar múltiples recuperaciones de archivos y sobrescribir de manera segura los archivos.

### 4.2 Cómo usar el menú emergente

Recuva ofrece diferentes opciones para seleccionar los documentos, archivos o carpetas que desea eliminar o sobrescribir de forma segura.

**La comprobación** generalmente se usa para seleccionar rápidamente varios archivos no contiguos o separados para recuperación o sobrescritura segura. 

**Resaltar** generalmente se utiliza para seleccionar rápidamente múltiples archivos contiguos en un bloque o grupo para recuperación o sobreescritura segura.

Haga clic derecho en un archivo eliminado que se muestra en Recuva para activar el siguiente Menú emergente: 
![image](tool_recuva21.png)

**Recuperar resaltado:** Este elemento le permite recuperar todos o cualquier archivo borrado resaltado.

**Recuperar comprobado:** Este elemento le permite recuperar un archivo borrado verificado.

**Marcar resaltado:** Este elemento le permite verificar un archivo borrado resaltado

**Desmarcar resaltado:** Este elemento le permite desmarcar un archivo borrado resaltado.

Como recordará, el Modo de visualización también se puede configurar en Pestaña General en la pantalla Opciones. Este elemento le permite seleccionar cómo le gustaría ver los archivos eliminados.

**Lista:** Esta opción le permite ver los archivos eliminados en una lista como en la Figura 5

**Árbol:** Esta opción le permite ver la ruta del directorio de los archivos eliminados en forma de un árbol expandible. 

**Miniaturas:** Esta opción le permite ver los archivos eliminados como gráficos o imágenes siempre que sea posible.

**Carpeta resaltada:** Esta opción le permite seleccionar varios archivos eliminados de acuerdo a su ruta de directorio, y le permite realizar las acciones enumeradas en el menú emergente en ellas.

**Sobrescritura segura resaltada:** Esta opción le permite sobrescribir de forma segura un archivo borrado resaltado.

**Comprobación de sobrescritura segura:** Esta opción le permite sobrescribir de forma segura un archivo borrado, cambiando su icono de estado a rojo.

### 4.3 Cómo sobrescribir de manera segura un archivo eliminado Archivo

Para sobrescribir de manera segura un archivo eliminado, realice los siguientes pasos:

**Paso 1.** 
Compruebe el archivo individual que desea que se sobrescriba de forma segura, y a continuación, haga clic con el botón derecho en la casilla de verificación para activar el menú emergente.

**Paso 2.** 
Seleccione "Seguro Sobrescribir comprobado" para activar el siguiente cuadro de diálogo de confirmación: 
![image](tool_recuva22.png) 

**Paso 3.** 
Haga clic en "Sí" para comenzar el proceso de sobreescritura; dependiendo del tamaño y el estado del archivo, así como de la opción Sobreescritura segura que seleccionó en la pestaña General en la pantalla _Opciones_ , esto podría Tómate un tiempo. Después de que se haya completado el proceso de sobrescritura, aparecerá una pantalla similar a la siguiente: 
![image](tool_recuva23.png)

Ha finalizado satisfactoriamente la recuperación y la sobrescritura segura de archivos con Recuva archivos eliminados previamente.

### 5 RECUVA PORTÁTIL

### 5.1 Diferencias entre las versiones instaladas y portátiles de Recuva

Dado que las herramientas portátiles no están instaladas en una computadora local, su existencia y uso pueden permanecer sin detectar . Sin embargo, tenga en cuenta que su dispositivo externo o dispositivo de memoria USB, y las herramientas portátiles son solo tan seguras como la computadora que está utilizando, y puede correr el riesgo de estar expuesto a adware, malware, spyware y virus.

Allí no hay otras diferencias entre Portable Recuva y la versión diseñada para ser instalada.

### 5.2 Cómo descargar y extraer Recuva Portable

Para comenzar a descargar y extraer Recuva Portable, realice los siguientes pasos:

**Paso 1.** Haga clic en [http://www.piriform.com/recuva/download/portable](http://www.piriform.com/recuva/download/portable) para ser dirigido al sitio de descarga apropiado, y active automáticamente la siguiente pantalla:

**Paso 2.** Haga clic en "OK" para guardar el archivo de instalación_rcsetupXXX.zip en su computadora; y luego vaya a él.

**Paso 3.** Haga clic con el botón derecho para activar el menú emergente de Windows y luego seleccione el elemento Extraer archivos ... como se muestra a continuación: 
![image](tool_recuva24.png)

**Paso 4.** Navegue hasta la unidad extraíble o la memoria USB como se muestra a continuación, y luego haga clic en "Nueva carpeta" para crear una nueva carpeta en la que extraer el archivo de instalación. 
![image](tool_recuva25.png)

**Paso 5.** Introduzca un nombre para la nueva carpeta en el documento árbol como se muestra a continuación: 
![image](tool_recuva26.png)

Alternativamente, puede escribir un nombre de carpeta en la lista desplegable adjunta: 
![image](tool_recuva27.png)

**Nota:** Aunque a los fines de este ejemplo, la nueva carpeta se titula Recuva Portable, los usuarios pueden elegir un nombre diferente.

**Paso 6.** Haga clic en "Aceptar" para comenzar a extraer su contenido a la carpeta recién creada.

**Paso 7.** Navegue hasta su unidad externa de destino o memoria USB, como se muestra a continuación, luego ábralo para confirmar que el Portable El programa Recuva se extrajo con éxito. 
![image](tool_recuva28.png)

**Paso 8.** Haga doble clic en _Recuva.exe_ para activar el Recuva portátil asistente.

Consulte el resto de la guía de la herramienta Recuva anterior para comenzar a configurarlo y usarlo.
