---
title: "SVGListBase-1.InsertItemBefore"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método de SVGListBase. Inserta un nuevo elemento en la lista en la posición especificada. El primer elemento es el número 0"
type: docs

url: /es/java/com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

Inserta un nuevo elemento en la lista en la posición especificada. El primer elemento es el número 0.

```java
public T InsertItemBefore(T newItem, ulong index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newItem | T | El elemento que se insertará en la lista. |
| index | UInt64 | El índice del elemento antes del cual se insertará el nuevo elemento. El primer elemento es el número 0. Si el índice es igual a 0, entonces el nuevo elemento se inserta al inicio de la lista. Si el índice es mayor o igual que numberOfItems, entonces el nuevo elemento se agrega al final de la lista. |

### Valor devuelto

El elemento insertado.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Código [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Generado cuando la lista no puede ser modificada. |

### Ver también

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
