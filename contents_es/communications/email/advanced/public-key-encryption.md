[Title]: # (Cifrado de clave pública)
[Order]: # (1)

PGP se basa en el concepto de cifrado de clave pública. Este es un sistema criptográfico que usa dos claves - una clave pública conocida por cualquiera y una clave privada conocida sólo por el destinatario del mensaje. Cuando Juan quiere enviar un mensaje seguro a Alicia, él usa la clave pública de Alicia para cifrar el mensaje. Luego Alicia usa su propia clave privada para descifrarlo.

*   Así que el cifrado de clave pública le permite cifrar y enviar mensajes de forma segura a cualquiera de quien conozca su clave pública.
*   Si otros conocen su clave pública, pueden enviarle mensajes que sólo usted puede descodificar.
*   Y si la gente conoce su clave pública, usted puede firmar mensajes de forma que esas personas sabrán que aquellos mensajes sólo podrían proceder de usted..
*   Y si usted conoce la clave pública de alguna otra persona, usted puede descodificar un mensaje firmado por esta, y saber que sólo puede proceder de esta persona.

Debe mantener su clave privada guardada en algún lugar seguro, y protegida con una contraseña larga (si alguien más obtiene una copia de su clave privada, puede hacerse pasar por usted y firmar mensajes en su nombre como si usted los hubiera escrito). Puede darle su clave pública a cualquiera que desee que pueda comunicarse de forma segura con usted, o a cualquiera que quiera poder distinguir si un mensaje proviene verdaderamente de usted.