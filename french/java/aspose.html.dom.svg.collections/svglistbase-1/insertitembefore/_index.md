---
title: "SVGListBase-1.InsertItemBefore"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode SVGListBase. Insère un nouvel élément dans la liste à la position spécifiée. Le premier élément est le numéro 0"
type: docs

url: /fr/java/com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

Insère un nouvel élément dans la liste à la position spécifiée. Le premier élément est le numéro 0.

```java
public T InsertItemBefore(T newItem, ulong index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| newItem | T | L'élément qui doit être inséré dans la liste. |
| index | UInt64 | L'index de l'élément avant lequel le nouvel élément doit être inséré. Le premier élément est le numéro 0. Si l'index est égal à 0, le nouvel élément est inséré au début de la liste. Si l'index est supérieur ou égal à numberOfItems, le nouvel élément est ajouté à la fin de la liste. |

### Valeur de retour

L'élément inséré.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Déclenché lorsque la liste ne peut pas être modifiée. |

### Voir aussi

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
