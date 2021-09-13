---
title: 'Lenguaje de programación de Zebra'
author: 
- Grupo ATIA
keywords: []
...

Antecedentes
============

El **lenguaje de programación de Zebra** (ZPL, _zebra programming language_) es un **lenguaje de descripción de página** [^1] propietario de la marca Zebra y es utilizado principalmente en aplicaciones de etiquetas. El lenguaje original fue reemplazado por ZPL II, sin embargo, no es completamente compatible con la versión anterior.

Más tarde, el **intérprete de BASIC de Zebra** (ZBI, _Zebra BASIC interpreter_) fue integrado en el software de impresoras y es visto como una mejora de ZPL II por los desarrolladores y está orientado a ANSI BASIC. Su princupal ventaja es que evita una reestructuración de código cuando se cambia de impresora en el caso el _software_ de la impresora anterior huniera sido hecho por algún competidor.

En otras palabas, para fines prácticos modernos **se debe de utilizar el formato ZBI en lo mayor posible**.

[^1]: Un **lenguaje de descripción de página** es un lenguaje que describe la apariencia de una página impresa en un nivel más elevado que una imagen en mapa de bits. Un par de ejemplos son PCL de HP, PostScript.

Fundamentos de ZBI
==================

ZBI-Developer es una IDE (_Integrated Development Environment_, entorno de desarrollo integrado) diseñado para ayudar en la creación, prueba y distribución de programas escritos en el formato ZBI. El IDE ofrece las siguientes funcionalidades:

- Control de proyectos.
- Ayuda de código por _pop-ups_.
- Impresoras virtuales para pruebas.
- Modos de escritura y _debug_.
- Distribución de programas a impresoras.
- Encriptación de programas para protección de datos propietarios.
- Importación de archivos desde impresoras hacia el IDE de desarrollo.
- Comparación de archivos.



Disponibilidad de versiones
---------------------------

El lenguaje **ZBI** consta de la versión 1.0 y la versión 2.0, dependiendo del modelo de la impresora puede que exista solo soporte para la versión 1.0 o para la verisón 2.0. Para determinar la versión se puede consultar la siguiente referencia:

### **Para ZBI versión 1.0 a 1.5**

La versión 1.x de ZBI está disponible en impresoras que cuentan con un _firmware_ con versión X.10 o superior (por ejemplo V48.10.x). Otra forma de determinar si ZBI versión 1.x es soportado es verificando la ausencia de una letra 'Z' en el nombre del _firmware_, es decir la versión V.60.13.0.13 soporta ZBI, mientras que V60.13.0.12Z no lo soporta. La siguiente lista muestra los modelos de impresoras que soportan ZBI 1.x.

- LP/TLP 284x-Z and 384x-Z
- S300/S400/S500/S600
- Z4000/Z6000
- Z4M/Z6M
- Z4Mplus/Z6Mplus
- 105SL
- PAX3
- XiII
- XiIII

