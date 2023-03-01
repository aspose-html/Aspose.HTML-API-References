---
title: HTMLTableSectionElement.InsertRow
second_title: Référence de l'API Aspose.HTML pour .NET
description: HTMLTableSectionElement méthode. Insérez une ligne dans cette section. La nouvelle ligne est insérée immédiatement avant le courantindice ème rangée dans cette section. Si indice est 1 ou égal au nombre de lignes dans cette section  la nouvelle ligne est ajoutée.
type: docs
weight: 70
url: /fr/net/aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Insérez une ligne dans cette section. La nouvelle ligne est insérée immédiatement avant le courant`indice` ème rangée dans cette section. Si `indice` est -1 ou égal au nombre de lignes dans cette section , la nouvelle ligne est ajoutée.

```csharp
public HTMLElement InsertRow(int index)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| index | Int32 | Le numéro de ligne où insérer une nouvelle ligne. Cet index commence à 0 et est relatif uniquement aux lignes contenues dans cette section, et non à toutes les lignes de la table. |

### Return_Value

La ligne nouvellement créée.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR : déclenché si l'index spécifié est supérieur au nombre de lignes ou si l'index est un nombre négatif autre que -1. @version DOM Niveau 2 |

### Voir également

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* espace de noms [Aspose.Html](../../htmltablesectionelement/)
* Assemblée [Aspose.HTML](../../../)


