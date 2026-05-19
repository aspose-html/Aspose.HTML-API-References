---
title: "ICSS2Properties.VerticalAlign"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "propiedad ICSS2Properties. Esta propiedad afecta la posición vertical dentro de una caja de línea de las cajas generadas por un elemento de nivel en línea. Los siguientes valores solo tienen significado respecto a un elemento de nivel en línea padre o a un elemento de nivel de bloque padre si ese elemento genera cajas en línea anónimas; no tienen efecto si no existe tal padre."
type: docs

url: /es/java/com.aspose.html.dom.css/icss2properties/verticalalign/
---
## ICSS2Properties.VerticalAlign property

Esta propiedad afecta la posición vertical dentro de una caja de línea de las cajas generadas por un elemento de nivel en línea. Los siguientes valores solo tienen significado respecto a un elemento de nivel en línea padre, o a un elemento de nivel de bloque padre, si ese elemento genera [cajas en línea anónimas](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#anonymous); no tienen efecto si no existe tal padre.

Nota. Los valores de esta propiedad tienen significados ligeramente diferentes en el contexto de tablas. Consulte la sección sobre [algoritmos de altura de tabla](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#height-layout) para obtener detalles. baseline - Alinea la línea base de la caja con la línea base de la caja padre. Si la caja no tiene línea base, alinea la parte inferior de la caja con la línea base del padre. middle - Alinea el punto medio vertical de la caja con la línea base de la caja padre más la mitad de la altura-x del padre. sub - Baja la línea base de la caja a la posición adecuada para subíndices de la caja del padre. (Este valor no afecta al tamaño de fuente del texto del elemento.) super - Eleva la línea base de la caja a la posición adecuada para superíndices de la caja del padre. (Este valor no afecta al tamaño de fuente del texto del elemento.) text-top - Alinea la parte superior de la caja con la parte superior de la fuente del elemento padre. text-bottom - Alinea la parte inferior de la caja con la parte inferior de la fuente del elemento padre. '[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Eleva (valor positivo) o baja (valor negativo) la caja por esta distancia (un porcentaje del valor de ['line-height'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-line-height)). El valor '0%' equivale a 'baseline'. '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - Eleva (valor positivo) o baja (valor negativo) la caja por esta distancia. El valor '0cm' equivale a 'baseline'. top - Alinea la parte superior de la caja con la parte superior de la caja de línea. bottom - Alinea la parte inferior de la caja con la parte inferior de la caja de línea.

```java
public String VerticalAlign { get; set; }
```

### Valor de retorno

propiedad vertical-align

### Ver también

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
