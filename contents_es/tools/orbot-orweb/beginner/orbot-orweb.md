[Title]: # ()
[Order]: # (0)

# GUÍA DE HERRAMIENTAS ORBOT Y ORWEB

## Orbot & Guía de herramientas de Orweb
Atención y anonimato en línea para Android

**Lección para leer:** [Internet](umbrella://lesson/the-internet)

**Ubicación de descarga:**
- Orbot: [https://guardianproject.info/apps/](https://guardianproject.info/apps/) o desde [Google Play](https://play.google.com/store/apps/details?id=org.torproject.android)
- Orweb: [https://guardianproject.info/apps/](https://guardianproject.info/apps /) o desde [Google Play](https://market.android.com/details?id=info.guardianproject.browser)
**Requisitos del teléfono:**
- Android 2.3 y versiones posteriores (Android 1.6 y hasta para Orweb)
**Versión utilizada en esta guía:**
- Orbot: 14.0.4.3
- Orweb: 0.6.1
**Licencia:**
- Orbot: Freeware - BSD
- Orweb: Software gratuito y de código abierto (GPL v3)
**Nivel:** Avanzado  
**Tiempo requerido:** 30-40 minutos  

**El uso de Orbot & Orweb combinado le dará:**
- La capacidad de ocultar su identidad digital de los sitios web que visitas
- La capacidad de ocultar los sitios web que visita de los proveedores de servicios de Internet (ISP) y otros mecanismos de vigilancia.
- La capacidad de eludir la censura de Internet y las reglas de filtrado.

**ORBOT**
![image](tool_orbot1.png)

### 1.1 Cosas que debe saber sobre esta herramienta antes que usted start

Orbot proporciona a los dispositivos Android acceso a Tor Network. Para obtener más información, consulte **[Lección de Internet](umbrella://lesson/the-internet)**

### 2.0 Cómo instalar Orbot

**Paso 1:** En su Android dispositivo, descargue e instale la aplicación desde [Google Play store here](https://play.google.com/store/apps/details?id=org.torproject.android).
![image](tool_orbot2.png)

**Paso 2:** Antes de que comience el proceso de instalación, se le pedirá que revise el acceso que tendrá la aplicación en su teléfono. Revisa esto cuidadosamente. Una vez que esté satisfecho con los permisos que se le otorgarán, presione "Aceptar" y la instalación se completará. Si no está de acuerdo con los permisos que se otorgarán, presione el botón Atrás y la instalación se cancelará.

### 2.1 Cómo configurar Orbot

Uso de Orbot por primera vez

**Paso 1:** Para abrir Orbot, toca el ícono de la aplicación.
![image](tool_orbot3.png)

**Paso 2:** Toca el idioma que quieras y luego toca "Siguiente".

**Paso 3:** Aparecerá un asistente de configuración con una descripción de Orbot. Léelo y pulse "Siguiente".

**Paso 4:** Luego se le mostrará una pantalla de advertencia. Una vez que hayas leído esto y entiendas los requisitos, toca "Siguiente".
![image](tool_orbot4.png)

**Paso 5:** Aparecerá una pantalla pidiéndote que concedas acceso al Superusuario Orbot. El acceso de superusuario requiere que su dispositivo esté rooteado si desea utilizar las funciones de proxy transparente de Orbot. No exploraremos esta función en la guía de Orbot. (Para obtener información acerca de rootear su teléfono, consulte **[Teléfonos móviles, lección de experto](umbrella://lesson/mobile-phones)**.)

Si su teléfono inteligente no está rooteado, solo marque la opción que indica _Lo entiendo y me gustaría continuar sin Superuser_. La siguiente pantalla explica que para que se beneficie de Tor, necesitará usar aplicaciones creadas para trabajar con Orbot, o que admitan el proxy HTTP o SOCKS.
![image](tool_orbot5.png)

**Paso 6:** Aparecerá una lista de aplicaciones que funcionan con Orbot. Tome nota de ellos y toque "Siguiente".
![image](tool_orbot6.png)

**Paso 7:** La configuración de Orbot está completa. Aparecerá una pantalla final que describirá los usuarios típicos de Tor y Orbot, una vez que haya leído este tocar "Finish".
![image](tool_orbot7.png)

**Paso 8:** Después de presionar "Finish" se le mostrará la pantalla de Orbot desactivada.
![image](tool_orbot8.png)

### 3.0 Uso básico

### 3.0.1 Inicio y detención de Orbot

**Paso 1:** Toque y mantenga presionado el icono gris de Orbot en el centro de la pantalla hasta que se ponga amarillo y diga _Orbot está comenzando_.
![image](tool_orbot9.png)

**Paso 2:** La primera vez que inicie Orbot aparecerá una notificación para confirmar que se conectó correctamente a la red Tor. Solo verá la pantalla de notificación la primera vez que inicie Orbot después de la instalación. Toque "OK" para ver la indicación de Orbot verde de que Orbot se está ejecutando.
![image](tool_orbot10.png)

**Paso 3:** Para desconectar Orbot toque y mantenga presionado el Orbot verde hasta se vuelve gris O si desea desconectarse y salir de Orbot, toque el ícono de menú (tres puntos verticales en la esquina superior derecha de la pantalla) en la esquina superior derecha de la pantalla y seleccione "Exit".
![image](tool_orbot11.png)

### 3.0.2 Navegar por Internet de forma anónima

Para navegar o chatear en Internet de forma anónima, debe instalar una aplicación que pueda enrutar su navegación a través de un proxy junto con Orbot. Esto es lo que Orbweb, la herramienta que se describe a continuación, hará por usted.

### 3.1 Uso avanzado

### 3.1.1 Nueva identidad

Si en cualquier etapa desea que parezca provenir de una nueva ubicación, puede obtener _nueva identidad_ de Orbot deslizando el dedo _left_ o _right_ en la imagen verde de Orbot. La imagen girará brevemente y luego mostrará _Has cambiado a una nueva Identidad Tor_.
![image](tool_orbot12.png)

### 3.1.2 Usando Bridges

Si el acceso a Tor está restringido o ilegal en su país, o si desea ocultar el hecho de que está utilizando Tor, puede configurar Orbot para usar puentes.

**Paso 1:** Toque el ícono con tres puntos escalonados en la parte superior de la pantalla para llevarlo a la pantalla de configuración.

**Paso 2:** Desplácese hacia abajo hasta la sección de puentes y marque la casilla junto a Usar puentes.
![image](tool_orbot13.png)

**Paso 3:** Toque la sección Bridges debajo de _Use Bridges_ para que se le presente una pantalla para ingresar la _IP address_ de _bridge_ que desea usar. Una vez ingresado correctamente, toque "OK". Reinicie Orbot para comenzar a utilizar _bridge_.
![image](tool_orbot14.png)

### 3.1.3 Inicio automático de Orbot

Para asegurarse de que nunca olvide iniciar Orbot, puede configurarse para iniciar cuando enciendes tu dispositivo Android.

**Paso 1:** Toca el icono con tres puntos escalonados en la parte superior de la pantalla para llevarlo a la pantalla de configuración.

**Paso 2:** Compruebe la opción _Start Orbot_ en el arranque en la parte superior de la pantalla de configuración.
![image](tool_orbot15.png)

**ORWEB**
![image](tool_orbot16.png)

### 1.1 Cosas que debe saber sobre esta herramienta antes de comenzar

Orweb es una aplicación para teléfono móvil de la plataforma Android, creada por The Guardian Project para navegar por Internet de forma anónima junto con Orbot.

**Nota:** Hay un error en la versión actual de Orweb (0.6.1 y anteriores) que puede filtrar información sobre usted, como su dirección IP, a los propietarios del sitio web si está viendo videos basados en HTML5. Orweb aún le permitirá eludir la censura y evitar que sea espiado por su proveedor de servicios de Internet (ISP), pero no lo recomendamos para ver sitios que puedan considerarse hostiles. Para obtener más información sobre el problema, consulte la respuesta de los desarrolladores.

Orweb solo funcionará correctamente después de instalar y configurar Orbot.

Recuerde, si creó previamente un correo o blog sin utilizar Orweb, el sitio aún conocerá su verdadero ubicación incluso si regresa utilizando Orweb.

Si desea un anonimato más fuerte al usar Orweb, deben tomarse otros pasos, como:
- Nunca acceder a cuentas creadas con su nombre real
- Nunca brinde sus datos personales
- Nunca haga las mismas cosas que cuando no intenta ser anónimo.

Para una alternativa que funcione con iOS en iPhone, use [OnionBrowser](https://mike.tig.as/onionbrowser/).

### 2.0 Cómo instalar Orweb

**Paso 1:** En su dispositivo Android, descargue e instale la aplicación desde [Google Play store here](https://play.google.com/store/apps/details?id=info.guardianproject.browser) al tocar "Instalar".
![image](tool_orbot17.png)

**Paso 2:** Antes de que comience el proceso de instalación, se le pedirá que revise el acceso que tendrá la aplicación en su teléfono. Revisa esto cuidadosamente. Una vez que esté satisfecho con los permisos que se le otorgarán, presione "Aceptar" para comenzar la instalación. Si no está de acuerdo con los permisos que se otorgarán, presione el botón Atrás y la instalación se cancelará.

**Paso 3:** Una vez que las descargas e instalación de Orweb se hayan completado, puede presionar "Abrir "para iniciar la aplicación.

### 3.0 Uso básico

**Usar Orweb por primera vez**

**Paso 1:** Para abrir Orweb, toque el ícono de la aplicación.
![image](tool_orbot18.png)

**Paso 2:** Orweb se iniciará y automáticamente intentará conectarse a _https://check.torproject.org_, para asegurarse de que esté conectado a la red Tor está trabajando. Si se puede conectar, verá un mensaje que le indicará que su _browser está configurado para usar Tor_. Si Orweb no puede conectarse al sitio web, verá un mensaje de error en el navegador. Si esto sucede, se sugiere que compruebe que Orbot esté instalado y funcionando corectly en su dispositivo Android si esto sucede.
![image](tool_orbot19.png)

**Paso 3:** Para navegar a sitios web, toque el área en la parte superior de la pantalla a la derecha del icono de Orweb y escriba la dirección que desea visitar. Presione "Ir" en el teclado en pantalla.
![image](tool_orbot20.png)

### 3.1 Uso avanzado

### 3.1.1 Cambiar el agente de usuario

Si desea ocultar el tipo de dispositivo que está utilizando en los sitios web que visita, Orweb se puede configurar para simular que es un número de dispositivos diferentes.

**Paso 1:** Toque el icono del menú (tres verticales puntos) que se encuentra en la parte superior derecha de la pantalla y toque "Configuración".
![imagen](tool_orbot21.png)

**Paso 2:** Una vez en la sección _settings_, desplácese hacia abajo hasta Sección de privacidad y toque "User Agent".
![image](tool_orbot22.png)

**Paso 3:** Aparecerá una lista de _User Agents_. Toque su elección (por ejemplo, toque _iPhone_ para configurarlo. Ahora, cada vez que visite un sitio web, pensará que está usando un _iPhone_).
![image](tool_orbot23.png)

### 3.1.2 Borrar historial de navegación

### 3.1.2.1 Manualmente

Para borrar manualmente su historial de navegación y caché, y para ocultar los sitios web que ha estado visitando en su teléfono, toque el ícono de menú (tres puntos verticales) y pulse "Borrar historial / caché".

### 3.1.2.2 Automáticamente

Para eliminar automáticamente su historial de navegación y caché a medida que vaya a una nueva página:

**Paso 1:** Toque el ícono de menú (tres puntos verticales) seguido de "Configuración".

**Paso 2:** En la pantalla de configuración, desplácese hacia abajo y toque _Clear Back History_.
![image](tool_orbot24.png)

**Nota:** Cuando configure esto, no podrá presionar el botón Atrás para ver las páginas web que ya ha visitado.

### 3.1.3 Borrar cookies

**Nota:** Al eliminar las cookies se cerrará la sesión desde cualquier sitio web en el que haya iniciado sesión.

**Paso 1:** Toque el icono de menú (tres ver puntos ticos) que se encuentran en la parte superior derecha de la pantalla y toque "Configuraciones".

**Paso 2:** Desplácese hacia abajo a la sección Cookies y presione "Borrar datos de cookies".

**Paso 3:** Toque "OK" para confirmar el borrado de las cookies.
![image](tool_orbot25.png)
