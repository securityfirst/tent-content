[Title]: # ()
[Difficulty]: # (Principiante)
[Order]: # (0)

# GUÍA DE HERRAMIENTAS DE PSIPHON

## Guía de herramientas de Psiphon
Exciencia de la atención

**Lección para leer:**
- [Internet](umbrella://lesson/the-internet)**
** Ubicación de descarga: ** [https://psiphon.ca/en/download.html](https://psiphon.ca/en/download.html)
** Requisitos de computadora: ** Una conexión a Internet, una computadora con Windows o un teléfono Android 2.2 o superior (las versiones de Psiphon 3 para iPhones y Mac OS X llegarán pronto)
** Versión utilizada en esta guía: ** Psiphon 3
** Licencia: ** Software de código abierto gratuito ; GNU GPL Versión 3
** Nivel: ** Principiante
** Otra lectura: ** [https://psiphon.ca/en/user-guide.html](https://psiphon.ca/en/ user-guide.html)
** Tiempo requerido: ** 5 minutos

** El uso de Psiphon le dará: **
- La capacidad de evitar la censura de Internet para acceder a sitios web y aplicaciones bloqueados en su teléfono o computadora.

### 1 Antes de comenzar

- **ALERTA:** El equipo Psiphon ha descubierto una instancia específica de malware disfrazada como un ejecutable de Psiphon 3 Windows. El malware se distribuye como un archivo comprimido llamado "pisphone3.zip" en www.copy.com y puede estar disponible en otras fuentes. El archivo zip contiene un archivo binario maligno denominado "pisphone3.exe" con las propiedades descritas en [Virus Total](https://www.virustotal.com/en/file/54201e181615c7eb18ee5a5ca3a0b7924cf3097ac5214fbee530741b6a6bc3da/analysis/1372262585/). Tenga en cuenta la falta de ortografía del nombre. Este ejecutable de Windows no está firmado digitalmente por Psiphon Inc. Nunca ejecute una nueva descarga de Psiphon sin verificar su firma digital, como se describe [aquí](https://psiphon.ca/en.html#is_my_psiphon_3_for_windows_authentic).
- Cabe señalar que aunque Psiphon no permite que las direcciones IP de los usuarios individuales se asocien con ningún sitio web visitado individualmente, Psiphon está destinado principalmente a ser una herramienta de evasión de censura, en lugar de una que garantiza el anonimato.

## # 2 Psiphon para Android

Descargue la versión apropiada de Psiphon desde [aquí](https://psiphon.ca/en/download.html).

Haga clic en un enlace de APK de Psiphon desde su correo electrónico o navegador de Android para comenzar la instalación.

(Si obtiene un error, es posible que deba [habilitar la carga lateral](https://psiphon.ca/en/faq.html#android-enable-sideloading).)

Cuando inicie el Psiphon aplicación, comenzará automáticamente a conectarse a la red Psiphon.

Cuando vea el Psiphon "P" al lado de una tecla en la esquina superior izquierda, indica que Psiphon se está ejecutando en modo VPN o Dispositivo completo y todas las aplicaciones están tunelizadas a través de Psiphon.

En la pestaña Estado, verá una P en el centro de la pantalla. El color de esta P indica el estado de conexión de Psiphon.
- Gris: conectando
- Rojo: no conectado
- Azul: conectado
![image](tool_psiphon1.png)

Para ejecutar Psiphon en el modo _Total Device_ Tunnel, debe tener Android 4.0+ o un Teléfono desbloqueado. Esta opción no está disponible para teléfonos no rooteados con una versión anterior de Android.

Una vez que la aplicación se haya conectado a la red, se ejecutará el navegador Psiphon incorporado. Psiphon para Android no canaliza automáticamente el tráfico para el navegador Android predeterminado u otras aplicaciones. Por defecto, solo el navegador Psiphon se tuneliza a través de la red Psiphon.
![Image](tool_psiphon2.png)

Una vez que el navegador Psiphon está abierto:
- La P en la parte superior izquierda le mostrará Psiphon ejecutándose
- La flecha en el centro izquierdo le permite cambiar entre las pestañas abiertas
- La X en la parte inferior de la página cierra la pestaña actual
- La estrella en la parte inferior de la página marca la página actual
- El + en la parte inferior de la página abre una nueva pestaña

### 3 Psiphon para Windows

Descargue la versión apropiada de Psiphon desde [aquí](https://psiphon.ca/en/download.html), y ejecuta el programa.

(Debería [verificar, aquí, que su copia de Psiphon para Windows es auténtica](https://psiphon.ca/en/faq.html#authentic-windows).)

Cuando la ejecute , debería ver un mensaje de seguridad que demuestre que este programa es un producto legítimo de Psiphon Inc.
![image](tool_psiphon3.png)

Psiphon comienza a conectarse automáticamente cuando lo ejecuta. Mientras se está conectando, se muestra un ícono giratorio.

Puedes seleccionar uno de los siguientes modos de túnel: **VPN, SSH o SSH +**

- Recomendamos que **selecciones la opción VPN**, lo que significa que todo tu tráfico se canaliza automáticamente a través de túneles. Psiphon.
- La diferencia clave entre SSH / SSH + y VPN es que SSH es específico de la aplicación, mientras que una VPN encripta todo el tráfico en su computadora. Con VPN, enciendes la VPN y luego todo tu tráfico se cifra para que el navegador web, Skype y el correo electrónico eviten la censura siempre que la VPN esté activada.
- En los modos SSH y SSH + de Psiphon, establece automáticamente la configuración de proxy y el tráfico para las aplicaciones que respetan estas configuraciones túnel a través de Psiphon. Estas configuraciones son respetadas por defecto por todos los principales navegadores web. La ofuscación SSH plus agrega una capa aleatorizada sobre SSH para evitar la toma de huellas dactilares del protocolo.
- En los modos SSH y SSH +, Psiphon ofrece una opción de división donde el tráfico internacional se tuneliza a través del proxy y el tráfico doméstico no. Compruebe la opción "No proxy ..." para habilitar la división de túneles. Cuando esta opción está activada, los dominios no procesados ​​se informan en el área de mensajes.
- Use las opciones SSH / SSH + si desea acceder rápidamente a los sitios nacionales y su modelo de amenaza lo permite. Sin embargo, recomendamos **seleccionar la opción de VPN**.

La conexión con el servidor de Psiphon se establece cuando el ícono de tilde verde se muestra a la izquierda de la ventana.
![image](tool_psiphon4.png)

Cuando cierra el programa, Psiphon se desconecta automáticamente. También puede hacer clic en el icono para alternar la conexión.

Recuerde que:
- Debido a que Psiphon 3 está basado en VPN, es capaz de realizar un proxy de todo su tráfico de Internet, no solo sitios web
- Tráfico entre su PC y el servidor VPN está encriptado, SIN EMBARGO el tráfico entre ese servidor y un sitio web no HTTPS no será encriptado. (Lo mismo se aplica a otros servicios de Internet, como cuando se conecta con Outlook o Thunderbird a un proveedor de correo electrónico que no es SSL.)
- Si no ha establecido una conexión, no está utilizando la VPN. El hecho de que tenga Psiphon 3 en su computadora en alguna parte no significa que sus solicitudes pasen por el proxy. 
- Las páginas web pueden cargarse más lentamente cuando se utiliza una VPN. Esto es normal y se debe a que el navegador no se conecta directamente al sitio web. Algunos servicios de VPN pagados pueden ser más rápidos que los gratuitos, como Psiphon 3, pero debe tener cuidado antes de confiar su información a una empresa, ya que podría ser compartido con otras organizaciones o vendido a otras compañías