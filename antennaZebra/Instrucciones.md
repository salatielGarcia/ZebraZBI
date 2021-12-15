Antes que nada instalar Code Sourcery para poder compilar aplicaciones en C. En el siguiente [link](https://developer.zebra.com/thread/30665) se descarga de manera directa.

Seguir los pasos descritos en el manual [link](https://www.zebra.com/apps/dlmanager?dlp=-227178c9720c025483893483886ea540bd07dd0f9873752cf891686eb4950400add13410300d57bc62ab30d9f72ea68d43274873e25f93f1a5d4aacc015691d2f11ccf24a7980cde3774ba08d55af95&c=us&l=en).

Para hacer la conexión remota desde el software basado en Eclipse es más sencillo utilizar la conexión por defecto 'FXSeries' que crear una nueva y modificacar las propiedades.

En la configuración, al parecer, se puede modificar la potencia de salida de 10 a 30dBm.

El archivo de ejemplo en C++ funciona al 100% con la configuración por default y se puede utilizar como referencia para el desarrollo de una app adicional.

La versión de C original marca errores.

Para ejecutar el código, revisar que se definan los _paths_ absolutos tanto de origen (Windows) como de destino (Linux) y asegurar que existen todas las carpetas donde será copiado el archivo elf.

Para integrar la configuración de la antena, recomiendan utilizar LLRP (_low level reader protocol_)
