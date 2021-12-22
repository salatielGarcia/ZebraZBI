# Impresoras ZT600 y 400

Se encuentra el la guía de programación RFID en [link](https://www.zebra.com/content/dam/zebra_new_ia/en-us/manuals/printers/common/programming/rfid3-pg-en.pdf).

## Guía de RFID

En la guía no hacen diferencia entre _tags_ e _inlays_.

### EPC

_Electronic Product Code_ es un estándar de numeración de productos administrada por GS1 para el uso de RFID. El código consiste en 96 bits el cual se liga a una base de datos en línea y esto permite compartir información de manera segura en toda la línea de producción.

Los campos que incluye el número EPC son:

- Encabezado.
- Número de manejo.
- Clase del objeto.
- Número de serie.

El comando ZPL ^RB se puede utilizar para definir la estructura EPC, la estructura se puede delimitar con los siguientes caracteres:

, ~ ! @ # $ % ^ & * | . < > / \ : ;

### Seguridad

Los passwords opcionales del tag constan de 32 bits y permiten acceder, bloquear o deshabilitar (matar) el tag. El comando ^RF se utiliza para establecer los passwords y ^RL para especificar el tipo de bloqueo.

### Selección de tags.

Hacer pruebas antes de comprar tags y revisar que el lugar donde se colocan no presenta interferencias para la lectura.

Características importantes antes de seleccionar un tag son:

- Cantidad de memoria programable.
- La forma en que los datos son segmentados.
- Comandos especificos que pueden ser utilizados.


