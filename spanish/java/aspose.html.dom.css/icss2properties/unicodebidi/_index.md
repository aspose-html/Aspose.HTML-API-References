---
title: "ICSS2Properties.UnicodeBidi"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad ICSS2Properties. Los valores de esta propiedad tienen los siguientes significados"
type: docs

url: /es/java/com.aspose.html.dom.css/icss2properties/unicodebidi/
---
## ICSS2Properties.UnicodeBidi property

Los valores de esta propiedad tienen los siguientes significados:

normal - El elemento no abre un nivel adicional de incrustación respecto al algoritmo bidireccional. Para elementos en línea, el reordenamiento implícito funciona a través de los límites del elemento.
embed - Si el elemento es en línea, este valor abre un nivel adicional de incrustación respecto al algoritmo bidireccional. La dirección de este nivel de incrustación se indica mediante la propiedad ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction). Dentro del elemento, el reordenamiento se realiza implícitamente. Esto corresponde a añadir un LRE (U+202A; para 'direction: ltr') o RLE (U+202B; para 'direction: rtl') al inicio del elemento y un PDF (U+202C) al final del elemento.
bidi-override - Si el elemento es en línea o un elemento de bloque que contiene solo elementos en línea, esto crea una sobrescritura. Esto significa que dentro del elemento, el reordenamiento se realiza estrictamente en secuencia según la propiedad ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction); la parte implícita del algoritmo bidireccional se ignora. Esto corresponde a añadir un LRO (U+202D; para 'direction: ltr') o RLO (U+202E; para 'direction: rtl') al inicio del elemento y un PDF (U+202C) al final del elemento.

```java
public String UnicodeBidi { get; set; }
```

### Valor devuelto

propiedad unicode-bidi

### Ver también

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
