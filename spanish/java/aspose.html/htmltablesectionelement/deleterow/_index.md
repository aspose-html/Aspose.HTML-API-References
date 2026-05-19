---
title: "HTMLTableSectionElement.DeleteRow"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "método de HTMLTableSectionElement. Elimina una fila de esta sección"
type: docs

url: /es/java/com.aspose.html/htmltablesectionelement/deleterow/
---
## HTMLTableSectionElement.DeleteRow method

Elimina una fila de esta sección.

```java
public void DeleteRow(int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice de la fila a eliminar, o -1 para eliminar la última fila. Este índice comienza en 0 y es relativo solo a las filas contenidas dentro de esta sección, no a todas las filas de la tabla. |

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Se produce si el índice especificado es mayor o igual que el número de filas o si el índice es un número negativo distinto de -1. @version DOM Level 2 |

### Ver también

* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
