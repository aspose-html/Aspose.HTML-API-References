---
title: "SVGListBase-1.RemoveItem"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode SVGListBase. Supprime un élément existant de la liste"
type: docs

url: /fr/java/com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

Supprime un élément existant de la liste.

```java
public T RemoveItem(ulong index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | UInt64 | L'indice de l'élément à supprimer. Le premier élément est le numéro 0. |

### Valeur de retour

L'élément supprimé.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Déclenché lorsque la liste ne peut pas être modifiée. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Déclenché si le numéro d'index est supérieur ou égal à numberOfItems. |

### Voir aussi

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
