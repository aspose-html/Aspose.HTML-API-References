---
title: "SVGListBase-1.Item"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété SVGListBase. Retourne l'élément d'indice dans la liste"
type: docs

url: /fr/java/com.aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Retourne l'élément d'indice dans la liste.

```java
public T this[ulong index] { get; set; }
```

| Paramètre | Description |
| --- | --- |
| index | Indice dans la liste. |

### Valeur de retour

L'objet stocké à la position d'indice dans la liste.

### Property Value

Le type d'élément stocké dans la liste.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Déclenché lorsque la liste ne peut pas être modifiée. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Déclenché si le numéro d'index est supérieur ou égal à numberOfItems. |

### Voir aussi

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
