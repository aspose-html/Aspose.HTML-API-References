---
title: HTMLTableElement.DeleteRow
second_title: Referencia de API de Aspose.HTML para .NET
description: HTMLTableElement método. Eliminar una fila de la tabla.
type: docs
weight: 190
url: /es/net/aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

Eliminar una fila de la tabla.

```csharp
public void DeleteRow(int index)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| index | Int32 | El índice de la fila que se va a eliminar. Este índice comienza desde 0 y es relativo al orden lógico (no al orden del documento) de todas las filas contenidas dentro de la tabla. Si el índice es -1, se elimina la última fila de la tabla. |

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: se genera si el índice especificado es mayor o igual al número de filas o si el índice es un número negativo distinto de -1. @versión DOM Nivel 2 |

### Ver también

* class [HTMLTableElement](../)
* espacio de nombres [Aspose.Html](../../htmltableelement/)
* asamblea [Aspose.HTML](../../../)


