---
title: "HTMLTableRowElement.InsertCell"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método HTMLTableRowElement. Inserta una celda TD vacía en esta fila. Si el índice es -1 o igual al número de celdas, la nueva celda se agrega al final"
type: docs

url: /es/java/com.aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

Insertar una celda `TD` vacía en esta fila. Si `index` es -1 o igual al número de celdas, la nueva celda se agrega al final.

```java
public HTMLElement InsertCell(int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El lugar donde insertar la celda, comenzando desde 0. |

### Valor de retorno

La celda recién creada.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Se produce si el `index` especificado es mayor que el número de celdas o si el índice es un número negativo distinto de -1. @version DOM Level 2 |

### Ver también

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
