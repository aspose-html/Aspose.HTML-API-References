---
title: HTMLTableSectionElement.DeleteRow
second_title: Referencia de API de Aspose.HTML para .NET
description: HTMLTableSectionElement método. Eliminar una fila de esta sección.
type: docs
weight: 60
url: /es/net/aspose.html/htmltablesectionelement/deleterow/
---
## HTMLTableSectionElement.DeleteRow method

Eliminar una fila de esta sección.

```csharp
public void DeleteRow(int index)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| index | Int32 | El índice de la fila a eliminar, o -1 para eliminar la última fila . Este índice comienza desde 0 y es relativo solo a las filas contenidas dentro de esta sección, no a todas las filas de la tabla. |

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: se genera si el índice especificado es mayor o igual al número de filas o si el índice es un número negativo distinto de -1. @versión DOM Nivel 2 |

### Ver también

* class [HTMLTableSectionElement](../)
* espacio de nombres [Aspose.Html](../../htmltablesectionelement/)
* asamblea [Aspose.HTML](../../../)


