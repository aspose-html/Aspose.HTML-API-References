---
title: SVGListBase1.Item
second_title: Referencia de API de Aspose.HTML para .NET
description: SVGListBase propiedad. Devuelve el elemento índice de la lista.
type: docs
weight: 10
url: /es/net/aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Devuelve el elemento índice de la lista.

```csharp
public T this[ulong index] { get; set; }
```

| Parámetro | Descripción |
| --- | --- |
| index | Índice en la lista. |

### Valor_devuelto

El objeto almacenado en la posición indexth en la lista.

### El valor de la propiedad

El tipo de elemento almacenado en list.

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Código[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Se genera cuando la lista no se puede modificar. |
| [DOMException](../../../aspose.html.dom/domexception/) | Código[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). Se genera si el número de índice es mayor o igual que numberOfItems. |

### Ver también

* class [SVGListBase&lt;T&gt;](../)
* espacio de nombres [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* asamblea [Aspose.HTML](../../../)


