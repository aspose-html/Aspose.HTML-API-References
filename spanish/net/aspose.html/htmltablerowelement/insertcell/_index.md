---
title: HTMLTableRowElement.InsertCell
second_title: Referencia de API de Aspose.HTML para .NET
description: HTMLTableRowElement método. Insertar un vacíoDT celda en esta fila. Si índice es 1 o igual al número de celdas se agrega la nueva celda .
type: docs
weight: 100
url: /es/net/aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

Insertar un vacío`DT` celda en esta fila. Si `índice` es -1 o igual al número de celdas, se agrega la nueva celda .

```csharp
public HTMLElement InsertCell(int index)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| index | Int32 | El lugar para insertar la celda, comenzando desde 0. |

### Valor_devuelto

La celda recién creada.

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Provocado si el especificado`índice` es mayor que el número de celdas o si el índice es un número negativo distinto de que -1. @versión DOM Nivel 2 |

### Ver también

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* espacio de nombres [Aspose.Html](../../htmltablerowelement/)
* asamblea [Aspose.HTML](../../../)


