---
title: "HTMLTableSectionElement.InsertRow"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "método de HTMLTableSectionElement. Inserta una fila en esta sección. La nueva fila se inserta inmediatamente antes de la fila actual en la posición index en esta sección. Si index es -1 o igual al número de filas en esta sección, la nueva fila se agrega al final."
type: docs

url: /es/java/com.aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Inserta una fila en esta sección. La nueva fila se inserta inmediatamente antes de la fila actual número `index` en esta sección. Si `index` es -1 o igual al número de filas en esta sección, la nueva fila se agrega al final.

```java
public HTMLElement InsertRow(int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El número de fila donde insertar una nueva fila. Este índice comienza en 0 y es relativo solo a las filas contenidas dentro de esta sección, no a todas las filas de la tabla. |

### Valor de retorno

La fila recién creada.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Se genera si el índice especificado es mayor que el número de filas o si el índice es un número negativo distinto de -1. @version DOM Level 2 |

### Ver también

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
