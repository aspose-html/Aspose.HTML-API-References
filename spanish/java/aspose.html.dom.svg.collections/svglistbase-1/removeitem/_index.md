---
title: "SVGListBase-1.RemoveItem"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método SVGListBase. Elimina un elemento existente de la lista"
type: docs

url: /es/java/com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

Elimina un elemento existente de la lista.

```java
public T RemoveItem(ulong index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | UInt64 | El índice del elemento que se debe eliminar. El primer elemento es el número 0. |

### Valor devuelto

El elemento eliminado.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Código [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Generado cuando la lista no puede ser modificada. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Código [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Generado si el número de índice es mayor o igual que numberOfItems. |

### Ver también

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
