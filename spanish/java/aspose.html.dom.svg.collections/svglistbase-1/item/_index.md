---
title: "SVGListBase-1.Item"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad SVGListBase. Devuelve el elemento en la posición índice de la lista"
type: docs

url: /es/java/com.aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Devuelve el elemento en la posición índice de la lista.

```java
public T this[ulong index] { get; set; }
```

| Parámetro | Descripción |
| --- | --- |
| index | Índice en la lista. |

### Valor devuelto

El objeto almacenado en la posición índice de la lista.

### Property Value

El tipo de elemento almacenado en la lista.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Código [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Generado cuando la lista no puede ser modificada. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Código [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Generado si el número de índice es mayor o igual que numberOfItems. |

### Ver también

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
