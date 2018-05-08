[Title]: # (Cifrado de llave pública)
[Order]: # (96)

# Cifrado de clave pública 

Los sistemas de cifrado tradicionales usan el mismo secreto o clave para cifrar y descifrar un mensaje. Entonces, si encriptara un archivo con la contraseña "bluetonicmonster", necesitaría tanto el archivo como el secreto "bluetonicmonster" para decodificarlo. El cifrado de clave pública utiliza dos claves: una para encriptar y otra para descifrar. Esto tiene todo tipo de consecuencias útiles. Por un lado, significa que puede entregar la clave para cifrar los mensajes para usted, y siempre que mantenga la otra clave en secreto, cualquier persona con esa clave puede hablar con usted de forma segura. La clave que distribuye ampliamente se conoce como "clave pública": de ahí el nombre de la técnica. El cifrado de clave pública se utiliza para cifrar correos electrónicos y archivos mediante Pretty Good Privacy (PGP), OTR para mensajería instantánea y SSL / TLS para navegación web.