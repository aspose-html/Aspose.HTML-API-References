---
title: "SVGListBase-1.ReplaceItem"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método SVGListBase. Reemplaza un elemento existente en la lista con un nuevo elemento"
type: docs

url: /es/java/com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

Reemplaza un elemento existente en la lista con un nuevo elemento.

```java
public T ReplaceItem(T newItem, ulong index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newItem | T | El elemento que se insertará en la lista. |
| index | UInt64 | El índice del elemento que se va a reemplazar. El primer elemento es el número 0. |

### Valor de retorno

El elemento insertado.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Código [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Generado cuando la lista no puede ser modificada. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Código [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Generado si el número de índice es mayor o igual que numberOfItems. |

### Ver también

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
