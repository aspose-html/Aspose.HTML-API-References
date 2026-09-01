---
title: "IXPathResult.SnapshotItem"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "método IXPathResult. Devuelve el elemento en la posición índice de la colección de instantáneas. Si el índice es mayor o igual que el número de nodos en la lista, este método devuelve null. A diferencia del resultado del iterador, la instantánea no se vuelve inválida pero puede no corresponder al documento actual si este se modifica."
type: docs

url: /es/java/com.aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Devuelve el elemento `index`‑ésimo de la colección de instantáneas. Si `index` es mayor o igual que el número de nodos en la lista, este método devuelve `null`. A diferencia del resultado del iterador, la instantánea no se invalida, pero puede no corresponder al documento actual si este se modifica.

```java
public Node SnapshotItem(int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Índice en la colección de instantáneas. |

### Valor devuelto

El nodo en la posición `index` de la `NodeList`, o `null` si no es un índice válido.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: se genera si `resultType` no es de tipo `UnorderedNodeSnapshot` o `OrderedNodeSnapshot`. |

### Ver también

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
