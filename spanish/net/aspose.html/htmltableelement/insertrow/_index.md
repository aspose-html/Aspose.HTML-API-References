---
title: HTMLTableElement.InsertRow
second_title: Referencia de API de Aspose.HTML para .NET
description: HTMLTableElement método. Inserta una nueva fila vacía en la tabla. La nueva fila se inserta inmediatamente antes y en la misma sección que la actual índice th fila en la tabla. Siíndice es 1 o igual al número de filas se agrega la nueva fila. Además cuando la tabla está vacía la fila se inserta en unTBODY que se crea e inserta en la tabla. Una fila de la tabla no puede estar vacía según HTML 4.01 .
type: docs
weight: 220
url: /es/net/aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

Inserta una nueva fila vacía en la tabla. La nueva fila se inserta inmediatamente antes y en la misma sección que la actual `índice` th fila en la tabla. Si`índice` es -1 o igual al número de filas, se agrega la nueva fila. Además, cuando la tabla está vacía, la fila se inserta en un`TBODY` que se crea e inserta en la tabla. Una fila de la tabla no puede estar vacía según [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224) ].

```csharp
public Node InsertRow(int index)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| index | Int32 | El número de fila donde insertar una nueva fila. Este índice comienza desde 0 y es relativo al orden lógico (no al orden del documento ) de todas las filas contenidas dentro de la tabla. |

### Valor_devuelto

La fila recién creada.

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: se genera si el índice especificado es mayor que el número de filas o si el índice es un número negativo distinto de -1. @versión DOM Nivel 2 |

### Ver también

* class [Node](../../../aspose.html.dom/node/)
* class [HTMLTableElement](../)
* espacio de nombres [Aspose.Html](../../htmltableelement/)
* asamblea [Aspose.HTML](../../../)


