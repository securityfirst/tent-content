[Title]: # ()
[Order]: # (0)

# GUÍA DE HERRAMIENTAS KEEPASSX

## KeePassX Guía de herramientas
Gestión segura de contraseñas

**Lección para leer: [Passwords](umbrella://lesson/passwords)**
**Ubicación de descarga:** [https://www.keepassx.org/downloads](https://www.keepassx.org/downloads)
**Requisitos de la computadora:** Windows 2000 o superior, Mac OS X 10.4-10.9
**Versión utilizada en esta guía:** KeePassX 0.4.3 (KeePassX es una versión multiplataforma del programa KeePass solo para Windows).
**Licencia:** Software gratuito y de código abierto (principalmente GPLv2)
**Otra lectura:** [https://www.keepassx.org/forum/](https://www.keepassx.org/forum/)
**Nivel:** Principiante
**Tiempo requerido:** 5 minutos

**El uso de KeePassX te dará:**

- La capacidad de guardar todas sus contraseñas en una base de datos conveniente y segura
- La capacidad de crear y almacenar muchas contraseñas fuertes sin tener que recordarlas

### 1.0 Cosas a considerar con KeePassX

KeePassX es una contraseña segura, un programa que puede usar para almacenar todas sus contraseñas para varios sitios web y servicios. Una contraseña segura es una gran herramienta porque le permite utilizar contraseñas diferentes difíciles de adivinar para todos sus servicios, sin necesidad de recordarlos. En cambio, solo necesita recordar una contraseña maestra que le permite descifrar una base de datos de todas sus contraseñas. Las cajas fuertes de contraseñas son convenientes y le permiten organizar todas sus contraseñas en una ubicación.

** Cabe señalar que el uso de una contraseña segura crea un único punto de falla y establece un objetivo obvio para los malos actores o adversarios. La investigación ha sugerido que muchas de las cajas fuertes de contraseñas comúnmente utilizadas tienen vulnerabilidades, así que tenga cuidado al determinar si esta es o no la herramienta adecuada para usted. **

### 1.1 Cómo funciona KeePassX

KeePassX funciona con archivos llamados bases de datos de contraseñas, que son exactamente lo que parecen: archivos que almacenan una base de datos de todas sus contraseñas. Estas bases de datos están encriptadas cuando están almacenadas en el disco duro de su computadora, por lo que si su computadora está apagada y alguien se la roba, no podrán leer sus contraseñas.

Las bases de datos de contraseñas se pueden encriptar a través de tres métodos: usando una contraseña maestra, usando un archivo de clave, o ambos. Veamos los pros y los contras de cada uno.

### 1.2 Usar una contraseña maestra

Una contraseña maestra actúa como una entrada de teclado para abrir la base de datos de contraseñas, necesita la contraseña maestra correcta. Sin él, nadie puede ver lo que hay dentro de la base de datos de contraseñas. Hay algunas cosas que debe tener en cuenta al usar una contraseña maestra para proteger su base de datos de contraseñas.

- _Esta contraseña descifrará todas sus contraseñas, ¡así que debe ser fuerte!_ Eso significa que no debería ser algo fácil de adivinar, y también debería ser larga, ¡mientras más, mejor! Además, cuanto más largo sea, menos tendrá que preocuparse por tener caracteres especiales o mayúsculas o números. Una contraseña que solo se compone de seis palabras aleatorias (en minúsculas, con espacios intermedios) puede ser más difícil de romper que una contraseña de 12 caracteres formada por letras mayúsculas y minúsculas, números y símbolos.
- _¡Necesitas poder recordar esta contraseña!_ Dado que esta única contraseña te permitirá acceder a todas tus otras contraseñas, debes asegurarte de que puedas recordarla sin escribirla. Esta es otra razón para utilizar algo como [Diceware](http://world.std.com/~reinhold/diceware.html). Puedes usar palabras regulares que sean fáciles de recordar, en lugar de tratar de recordar combinaciones de símbolos no naturales y mayúsculas

### 1.3 Uso de un archivo de claves

Alternativamente, puede usar un archivo de claves para encriptar su base de datos de contraseñas. Un archivo de claves actúa de la misma manera que una contraseña: cada vez que desee descifrar su base de datos de contraseñas deberá proporcionar ese archivo de claves a KeePassX. Un archivo de clave debe almacenarse en una unidad USB u otro medio portátil, y solo debe insertarse en su computadora cuando desee abrir su base de datos de contraseñas. El beneficio de esto es que incluso si alguien accede al disco duro de su computadora (y, por lo tanto, a su base de datos de contraseñas), aún no podrá descifrarlo sin el archivo de claves almacenado en los medios externos. (Además, un archivo de clave puede ser mucho más difícil de adivinar para un adversario que una contraseña normal). El inconveniente es que cada vez que desee acceder a su base de datos de contraseñas, necesitará tener ese medio externo a mano (y si lo pierde) o se daña, entonces no podrás abrir tu base de datos de contraseñas).

Usar un archivo de claves en lugar de una contraseña es lo más parecido a tener una clave física real para abrir su base de datos de contraseñas; todo lo que necesita hacer es insertar su unidad USB, seleccionar el archivo de claves y ¡listo! Sin embargo, si eliges usar un archivo de clave en lugar de una contraseña maestra, asegúrate de que tu unidad USB esté almacenada en un lugar seguro: cualquier persona que descubra que podrá abrir tu base de datos de contraseñas.

### 1.4 Usando ambos

El método más seguro para encriptar su base de datos de contraseñas es usar una contraseña maestra y un archivo de claves. De esta forma, su capacidad para descifrar su base de datos de contraseñas depende de lo que sabe (su contraseña maestra) y de lo que tiene (su archivo de claves), y cualquier entidad maliciosa que desee obtener acceso a sus contraseñas necesitará ambas. (Dicho esto, tenga en cuenta su modelo de amenaza: para la mayoría de los usuarios domésticos que solo desean almacenar sus contraseñas, una contraseña maestra sólida debería ser suficiente. Pero si está preocupado por proteger contra los actores estatales con acceso a enormes recursos informáticos recursos, entonces cuanta más seguridad, mejor.)

Ahora que comprende cómo funciona KeePassX, ¡comencemos a usarlo realmente!

### 2.0 Primeros pasos con KeePassX

Una vez que haya instalado KeePassX desde [aquí](https://www.keepassx.org/downloads), continúe y ejecútelo.

Una vez que se haya iniciado, seleccione "Nueva base de datos" en el menú Archivo.

Aparecerá un cuadro de diálogo que le pedirá que ingrese una contraseña maestra y/o use un archivo de claves. Seleccione las casillas de verificación apropiadas según su elección.

Tenga en cuenta que si desea ver la contraseña que está escribiendo (en lugar de oscurecerla con puntos) puede hacer clic en el botón con el "ojo" a la derecha.

También tenga en cuenta que puede usar cualquier archivo existente como archivo de claves; una imagen de su gato, por ejemplo, podría usarse como un archivo de claves. Solo deberá asegurarse de que el archivo que elija nunca se modifique, porque si se cambia su contenido, ya no funcionará para descifrar su base de datos de contraseñas.

También tenga en cuenta que a veces abrir un archivo en otro programa puede ser suficiente para modificarlo; la mejor práctica es no abrir el archivo, excepto para desbloquear KeePassX. (Sin embargo, es seguro mover o cambiar el nombre del archivo de claves).

Una vez que haya inicializado con éxito su base de datos de contraseñas, debe guardarla seleccionando "Guardar base de datos" en el menú Archivo. (Tenga en cuenta que si lo desea, puede mover el archivo de la base de datos de contraseñas más adelante a donde desee en su disco duro, o moverlo a otras computadoras; aún podrá abrirlo usando KeePassX y la contraseña/archivo de claves que especificó antes .)

### 2.1 Organización de contraseñas

KeePassX le permite organizar contraseñas en "Grupos", que básicamente son solo carpetas. Puede crear, eliminar o editar Grupos o Subgrupos yendo al menú "Grupos" en la barra de menú, o haciendo clic con el botón derecho en un Grupo en el panel izquierdo de la ventana de KeePassX. La agrupación de contraseñas no afecta a ninguna de las funciones de KeePassX; es solo una práctica herramienta de organización.

### 2.2 Almacenamiento/generación/edición de contraseñas

Para crear una nueva contraseña o almacenar una contraseña que ya tiene, haga clic derecho en el Grupo en el que desea almacenar la contraseña y elija "Agregar nueva entrada" (también puede elegir "Entradas> Agregar nueva entrada" en la barra de menú ) Para el uso básico de la contraseña, haga lo siguiente:

- Ingrese un título descriptivo que puede usar para reconocer esta entrada de contraseña en el campo "Título".
- Ingrese el nombre de usuario asociado con esta entrada de contraseña en el campo "Nombre de usuario". (Esto puede estar en blanco si no hay un nombre de usuario).
- Ingrese su contraseña en el campo "Contraseña". Si está creando una nueva contraseña (es decir, si se registra para un nuevo sitio web y desea crear una nueva y única contraseña aleatoria), haga clic en el botón "Generar" a la derecha. Aparecerá un cuadro de diálogo generador de contraseñas, que puede usar para generar una contraseña aleatoria. Hay varias opciones en este cuadro de diálogo, incluido el tipo de caracteres que se incluirán y el tiempo necesario para crear la contraseña.
 * Tenga en cuenta que si genera una contraseña aleatoria, no es necesario que recuerde (¡ni siquiera sepa!) Cuál es esa contraseña. KeePassX lo almacena por usted, y en cualquier momento que lo necesite podrá copiarlo/pegarlo en el programa apropiado. Este es el objetivo de una contraseña segura: puede usar diferentes contraseñas aleatorias largas para cada sitio/servicio, sin siquiera saber cuáles son las contraseñas.
 * Debido a esto, debe crear la contraseña siempre que el servicio permita y use tantos tipos diferentes de caracteres como sea posible.
 * Una vez que esté satisfecho con las opciones, haga clic en "Generar" en la esquina inferior derecha para generar la contraseña, y luego haga clic en "Aceptar". La contraseña aleatoria generada se ingresará automáticamente en los campos "Contraseña" y "Repetir". (Si no está generando una contraseña aleatoria, deberá ingresar nuevamente la contraseña elegida en el campo "Repetir").
- Por último, haz clic en "Aceptar". Su contraseña ahora está almacenada en su base de datos de contraseñas. Para asegurarse de que se guardan los cambios, asegúrese de guardar la base de datos de contraseñas editada yendo a "Archivo> Guardar base de datos". (Alternativamente, si cometió un error, puede cerrar y luego volver a abrir el archivo de la base de datos y se perderán todos los cambios).

Si alguna vez necesita cambiar/editar la contraseña almacenada, puede simplemente elegir el Grupo en el que está y hacer doble clic en su título en el panel derecho, y el cuadro de diálogo "Nueva entrada" aparecerá de nuevo.

### 2.3 Uso normal

Para usar una entrada en su base de datos de contraseñas, simplemente haga clic derecho en la entrada y elija "Copiar nombre de usuario al portapapeles" o "Copiar contraseña al portapapeles", y luego vaya a la ventana/sitio web donde desea ingresar su nombre de usuario/contraseña, y simplemente pegue en el campo apropiado. (En lugar de hacer clic con el botón derecho en la entrada, también puede hacer doble clic en el nombre de usuario o la contraseña de la entrada que desea, y el nombre de usuario o la contraseña se copiarán automáticamente en el portapapeles).

### 2.4 Uso avanzado

Una de las características más útiles de KeePassX es que puede escribir automáticamente nombres de usuario y contraseñas para usted en otros programas cuando presiona una combinación especial de teclas en su teclado. Tenga en cuenta que aunque esta característica solo está disponible en Linux, otras cajas fuertes con contraseñas como KeePass (en la que se basó KeePassX) admiten esta característica en otros sistemas operativos, y funciona de manera similar.

Para habilitar esta característica, haga lo siguiente.

 _1. Elige tu tecla de acceso rápido global. Selecciona "Configuración" en el menú "Extras" y luego elige "Avanzado" en el panel de la izquierda. Haga clic dentro del campo "Acceso directo de tipo automático global" y luego presione la combinación de teclas de método abreviado que desea usar. (Por ejemplo, mantenga presionadas las teclas Ctrl, Alt y Shift, y luego presione "p". Puede usar cualquier combinación de teclas que desee, pero querrá asegurarse de que no entre en conflicto con las teclas rápidas que utilizan otras aplicaciones, así que trate de mantenerse alejado de cosas como Ctrl + X o Alt + F4.) Una vez que esté satisfecho, haga clic en "Aceptar".

 _2. Configure el tipo automático para una contraseña específica. Asegúrese de que tiene la ventana abierta donde desea ingresar la contraseña. Luego vaya a KeePassX, busque la entrada para la cual desea habilitar el tipo automático, y haga doble clic en el título de la entrada para abrir el cuadro de diálogo "Nueva entrada".

 _3._ Haga clic en el botón "Herramientas" en la parte inferior izquierda, y seleccione "Tipo automático: seleccione la ventana de destino". En el diálogo que aparece, expanda el cuadro desplegable y elija el título de la ventana en la que desea ingresar el nombre de usuario y la contraseña. Haga clic en Aceptar y luego en Aceptar de nuevo.

¡Pruébalo! _ Ahora, para autenticar tu nombre de usuario y contraseña, dirígete a la ventana/sitio web donde deseas que KeePassX configure automáticamente tu nombre de usuario/contraseña. Asegúrate de que el cursor esté en el cuadro de texto de tu nombre de usuario, y luego presiona la combinación de teclas que seleccionaste arriba para la tecla de acceso directo global. Siempre que KeePassX esté abierto (incluso si está minimizado o no está enfocado), su nombre de usuario y contraseña deben ingresarse automáticamente.

Tenga en cuenta que, dependiendo de cómo esté configurado el sitio web/la ventana, es posible que esta característica no funcione al 100% correctamente desde el principio. (Podría ingresar el nombre de usuario, pero no la contraseña, por ejemplo). Aunque puede solucionar problemas y personalizar esta característica, para obtener más información, le recomendamos consultar la documentación de KeePass [aquí](http://keepass.info/help/base) /autotipo.html). (Aunque hay algunas diferencias entre KeePass y KeePassX, esa página debería ser suficiente para guiarlo en la dirección correcta).

Se recomienda que use una combinación de teclas que sea difícil de golpear accidentalmente. ¡No querrás pegar accidentalmente la contraseña de tu cuenta bancaria en una publicación de Facebook!

### 2.5 Otras características

Puede buscar en su base de datos escribiendo algo en el cuadro de búsqueda (el cuadro de texto en la barra de herramientas de la ventana principal de KeePassX) y presionando enter.

También puede ordenar sus entradas haciendo clic en el encabezado de la columna en la ventana principal.

También puede "bloquear" KeePassX seleccionando "Archivo> Bloquear área de trabajo" para que pueda dejar abierto KeePassX, pero solicite su contraseña maestra (y/o archivo de claves) antes de que pueda acceder nuevamente a su base de datos de contraseñas. También puede hacer que KeePassX se bloquee automáticamente después de un cierto período de inactividad. Esto puede evitar que alguien acceda a sus contraseñas si se aleja de su computadora. Para habilitar esta función, elija "Extras> Configuración" en el menú y haga clic en las opciones de seguridad. Luego marque la casilla que dice "Bloquear base de datos después de inactividad de {número} segundos".

KeePassX también puede almacenar más que solo nombres de usuario y contraseñas. Por ejemplo, puede crear entradas para almacenar cosas importantes como números de cuenta, claves de producto, números de serie o cualquier otra cosa. No es necesario que los datos que ingresa en el campo "Contraseña" tengan que ser una contraseña. Puede ser cualquier cosa que desee: simplemente ingrese lo que desea almacenar en el campo "Contraseña" en lugar de una contraseña real (y deje el campo "Nombre de usuario" en blanco si no hay ningún nombre de usuario) y KeePassX lo recordará de manera segura y segura.