---
title: "ICSS2Properties.Display"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad ICSS2Properties. Los valores de esta propiedad tienen los siguientes significados"
type: docs

url: /es/java/com.aspose.html.dom.css/icss2properties/display/
---
## ICSS2Properties.Display property

Los valores de esta propiedad tienen los siguientes significados:

block - Este valor hace que un elemento genere una caja de bloque principal.inline - Este valor hace que un elemento genere una o más cajas inline.list-item - Este valor hace que un elemento (p. ej., LI en HTML) genere una caja de bloque principal y una caja inline de tipo list-item. Para información sobre listas y ejemplos de formato de listas, consulte la sección sobre [lists](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#lists).marker - Este valor declara [generated content](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html) antes o después de una caja como un marcador. Este valor solo debe usarse con los pseudo‑elementos [:before y :after](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#before-after-content) adjuntos a elementos de nivel de bloque. En otros casos, este valor se interpreta como 'inline'. Consulte la sección sobre [markers](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#markers) para más información.none - Este valor hace que un elemento no genere cajas en la [formatting structure](https://www.w3.org/TR/1998/REC-CSS2-19980512/intro.html#formatting-structure) (es decir, el elemento no afecta al diseño). Los elementos descendientes tampoco generan cajas; este comportamiento no puede sobrescribirse estableciendo la propiedad ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) en los descendientes. Tenga en cuenta que un display de 'none' no crea una caja invisible; no crea ninguna caja. CSS incluye mecanismos que permiten que un elemento genere cajas en la estructura de formato que afectan al formato pero no son visibles. Consulte la sección sobre [visibility](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#visibility) para más detalles.run-in and compact - Estos valores crean cajas block o inline, según el contexto. Las propiedades se aplican a cajas run‑in y compact según su estado final (nivel inline o bloque). Por ejemplo, la propiedad ['white-space'](https://www.w3.org/TR/1998/REC-CSS2-19980512/text.html#propdef-white-space) solo se aplica si la caja se convierte en una caja block.table, inline-table, table-row-group, [table-column](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#value-def-table-column), table-column-group, table-header-group, table-footer-group, table-row, table-cell y table-caption - Estos valores hacen que un elemento se comporte como un elemento de tabla (sujeto a restricciones descritas en el capítulo sobre [tables](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html)).

```java
public String Display { get; set; }
```

### Valor de retorno

propiedad display

### Ver también

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
