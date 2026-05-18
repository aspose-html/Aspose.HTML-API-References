---
title: "SVGListBase-1.ReplaceItem"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode SVGListBase. Remplace un élément existant dans la liste par un nouvel élément"
type: docs

url: /fr/java/com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

Remplace un élément existant dans la liste par un nouvel élément.

```java
public T ReplaceItem(T newItem, ulong index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| newItem | T | L'élément qui doit être inséré dans la liste. |
| index | UInt64 | L'index de l'élément à remplacer. Le premier élément est le numéro 0. |

### Valeur de retour

L'élément inséré.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Déclenché lorsque la liste ne peut pas être modifiée. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Déclenché si le numéro d'index est supérieur ou égal à numberOfItems. |

### Voir aussi

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
