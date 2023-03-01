---
title: SVGListBase1.Item
second_title: Référence de l'API Aspose.HTML pour .NET
description: SVGListBase propriété. Renvoie lélément dindex de la liste.
type: docs
weight: 10
url: /fr/net/aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Renvoie l'élément d'index de la liste.

```csharp
public T this[ulong index] { get; set; }
```

| Paramètre | La description |
| --- | --- |
| index | Index dans la liste. |

### Return_Value

L'objet stocké à la position d'index dans la liste.

### Valeur de la propriété

Le type d'élément stocké dans la liste.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Code[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Levé lorsque la liste ne peut pas être modifiée. |
| [DOMException](../../../aspose.html.dom/domexception/) | Code[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). Déclenché si le numéro d'index est supérieur ou égal à numberOfItems. |

### Voir également

* class [SVGListBase&lt;T&gt;](../)
* espace de noms [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* Assemblée [Aspose.HTML](../../../)


