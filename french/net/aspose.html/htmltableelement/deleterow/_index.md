---
title: DeleteRow
second_title: Référence de l'API Aspose.HTML pour .NET
description: Supprimer une ligne de tableau.
type: docs
weight: 190
url: /fr/net/aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

Supprimer une ligne de tableau.

```csharp
public void DeleteRow(int index)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| index | Int32 | Index de la ligne à supprimer. Cet index commence à partir de 0 et est relatif à l'ordre logique (et non à l'ordre du document) de toutes les lignes contenues dans la table. Si l'index est -1, la dernière ligne de la table est supprimée. |

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception) | INDEX_SIZE_ERR : Levé si l'index spécifié est supérieur ou égal au nombre de lignes ou si l'index est un nombre négatif autre que -1. @version DOM niveau 2 |

### Voir également

* class [HTMLTableElement](../../htmltableelement)
* espace de noms [Aspose.Html](../../htmltableelement)
* Assemblée [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->