---
title: "SVGListBase-1.GetItem"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método SVGListBase. Devuelve el elemento especificado de la lista"
type: docs

url: /es/java/com.aspose.html.dom.svg.collections/svglistbase-1/getitem/
---
## SVGListBase&lt;T&gt;.GetItem method

Devuelve el elemento especificado de la lista.

```java
public T GetItem(ulong index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | UInt64 | El índice del elemento de la lista que se debe devolver. El primer elemento es el número 0. |

### Valor devuelto

El elemento seleccionado.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Código [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Generado si el número de índice es mayor o igual que numberOfItems. |

### Ver también

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
