---
title: "ICSS2Properties.TextShadow"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad ICSS2Properties. Esta propiedad acepta una lista separada por comas de efectos de sombra que se aplicarán al texto del elemento. Los efectos de sombra se aplican en el orden especificado y pueden superponerse entre sí, pero nunca superpondrán el propio texto. Los efectos de sombra no alteran el tamaño de una caja, pero pueden extenderse más allá de sus límites. El nivel de apilamiento de los efectos de sombra es el mismo que el del propio elemento"
type: docs

url: /es/java/com.aspose.html.dom.css/icss2properties/textshadow/
---
## ICSS2Properties.TextShadow property

Esta propiedad acepta una lista separada por comas de efectos de sombra que se aplicarán al texto del elemento. Los efectos de sombra se aplican en el orden especificado y pueden superponerse entre sí, pero nunca superpondrán el propio texto. Los efectos de sombra no alteran el tamaño de una caja, pero pueden extenderse más allá de sus límites. El [nivel de apilamiento](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#stack-level) de los efectos de sombra es el mismo que el del propio elemento.

Cada efecto de sombra debe especificar un desplazamiento de sombra y puede opcionalmente especificar un radio de desenfoque y un color de sombra.

Un desplazamiento de sombra se especifica con dos valores de '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' que indican la distancia desde el texto. El primer valor de longitud especifica la distancia horizontal a la derecha del texto. Un valor de longitud horizontal negativo coloca la sombra a la izquierda del texto. El segundo valor de longitud especifica la distancia vertical debajo del texto. Un valor de longitud vertical negativo coloca la sombra encima del texto.

Un radio de desenfoque puede especificarse opcionalmente después del desplazamiento de sombra. El radio de desenfoque es un valor de longitud que indica los límites del efecto de desenfoque. El algoritmo exacto para calcular el efecto de desenfoque no está especificado.

Un valor de color puede especificarse opcionalmente antes o después de los valores de longitud del efecto de sombra. El valor de color se usará como base para el efecto de sombra. Si no se especifica color, se usará el valor de la propiedad ['color'](https://www.w3.org/TR/1998/REC-CSS2-19980512/colors.html#propdef-color) en su lugar.

```java
public String TextShadow { get; set; }
```

### Valor de retorno

propiedad text-shadow

### Ver también

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
