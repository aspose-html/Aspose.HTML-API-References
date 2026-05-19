---
title: "HTMLTableElement.InsertRow"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método de HTMLTableElement. Inserta una nueva fila vacía en la tabla. La nueva fila se inserta inmediatamente antes y en la misma sección que la fila actual de índice dado en la tabla. Si el índice es -1 o igual al número de filas, la nueva fila se agrega al final. Además, cuando la tabla está vacía, la fila se inserta en un `TBODY` que se crea e inserta en la tabla. Una fila de tabla no puede estar vacía según HTML 4.01."
type: docs

url: /es/java/com.aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

Inserta una nueva fila vacía en la tabla. La nueva fila se inserta inmediatamente antes y en la misma sección que la fila actual `index` de la tabla. Si `index` es -1 o igual al número de filas, la nueva fila se agrega al final. Además, cuando la tabla está vacía, la fila se inserta en un `TBODY` que se crea y se inserta en la tabla. Una fila de tabla no puede estar vacía según [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)].

```java
public Node InsertRow(int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El número de fila donde insertar una nueva fila. Este índice comienza en 0 y es relativo al orden lógico (no al orden del documento) de todas las filas contenidas dentro de la tabla. |

### Valor de retorno

La fila recién creada.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Se produce si el índice especificado es mayor que el número de filas o si el índice es un número negativo distinto de -1. @version DOM Level 2 |

### Ver también

* class [Node](../../../com.aspose.html.dom/node/)
* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
