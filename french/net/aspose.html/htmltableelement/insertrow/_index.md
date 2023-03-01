---
title: HTMLTableElement.InsertRow
second_title: Référence de l'API Aspose.HTML pour .NET
description: HTMLTableElement méthode. Insérer une nouvelle ligne vide dans le tableau. La nouvelle ligne est insérée immédiatement avant et dans la même section que la actuelleindice ème ligne du tableau. Siindice est 1 ou égal au nombre de lignes la nouvelle ligne est ajoutée. De plus lorsque la table est vide la ligne est insérée dans unCORPS qui est créé et inséré dans le tableau. Une ligne de tableau ne peut pas être vide selon HTML 4.01 .
type: docs
weight: 220
url: /fr/net/aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

Insérer une nouvelle ligne vide dans le tableau. La nouvelle ligne est insérée immédiatement avant et dans la même section que la actuelle`indice` ème ligne du tableau. Si`indice` est -1 ou égal au nombre de lignes, la nouvelle ligne est ajoutée. De plus, lorsque la table est vide la ligne est insérée dans un`CORPS` qui est créé et inséré dans le tableau. Une ligne de tableau ne peut pas être vide selon [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224) ].

```csharp
public Node InsertRow(int index)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| index | Int32 | Le numéro de ligne où insérer une nouvelle ligne. Cet index commence à 0 et est relatif à l'ordre logique (et non l'ordre du document ) de toutes les lignes contenues dans la table. |

### Return_Value

La ligne nouvellement créée.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR : déclenché si l'index spécifié est supérieur au nombre de lignes ou si l'index est un nombre négatif autre que -1. @version DOM niveau 2 |

### Voir également

* class [Node](../../../aspose.html.dom/node/)
* class [HTMLTableElement](../)
* espace de noms [Aspose.Html](../../htmltableelement/)
* Assemblée [Aspose.HTML](../../../)


