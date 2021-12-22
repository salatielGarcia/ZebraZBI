
---
title: 'Curso RFID'
author: 
- Grupo ATIA
keywords: []
output:
- html_document:
    number_sections: true
- pdf_document:
    number_sections: true
documentclass: article
papersize: a4
linestretch: 1.3
fontsize: 12pt
links-as-notes: false
geometry:
- margin=20mm
...

Fundamentos de RF
=================

Alta frecuencia
---------------

De manera regular, un circuito se puede analizar por medio de las ecuaciones de Kirchoff. Sin embargo, conforme la frecuaencia de operación aumenta no es posible suponer que el voltaje (o corriente) en un punto de un conductor es igual que en otro punto.

Esto va en relación a la longitud de onda [@eq:waveLenght].

$$ \lambda = \frac{c}{f} $$ {#eq:waveLenght}

donde $c$ es $3\times 10^8m/s = 299 792 458m/s$. Cuando la longitud de onda se encuentra en el mismo orden de tamaño que el circuito, no se puede asumir que el voltaje a lo largo de todo el conductor es el mismo y se debe empezar a analizar como una **línea de transmisión**.

![Longitud de onda en un circuito.](.\img\waveLenght.png){#fig:waveLenght width=50%}


Tags RFID
---------


