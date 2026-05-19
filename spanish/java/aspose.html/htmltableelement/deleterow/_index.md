---
title: "HTMLTableElement.DeleteRow"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método de HTMLTableElement. Elimina una fila de tabla."
type: docs

url: /es/java/com.aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

Elimina una fila de tabla.

```java
public void DeleteRow(int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice de la fila a eliminar. Este índice comienza en 0 y es relativo al orden lógico (no al orden del documento) de todas las filas contenidas en la tabla. Si el índice es -1 se elimina la última fila de la tabla. |

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Se produce si el índice especificado es mayor o igual que el número de filas o si el índice es un número negativo distinto de -1. @version DOM Level 2 |

### Ver también

* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
