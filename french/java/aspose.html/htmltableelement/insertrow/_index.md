---
title: "HTMLTableElement.InsertRow"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "HTMLTableElement method. Insère une nouvelle ligne vide dans le tableau. La nouvelle ligne est insérée immédiatement avant et dans la même section que la ligne d'index actuelle du tableau. Si l'index vaut -1 ou est égal au nombre de lignes, la nouvelle ligne est ajoutée à la fin. De plus, lorsque le tableau est vide, la ligne est insérée dans un `TBODY` qui est créé et inséré dans le tableau. Une ligne de tableau ne peut pas être vide selon HTML 4.01"
type: docs

url: /fr/java/com.aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

Insère une nouvelle ligne vide dans le tableau. La nouvelle ligne est insérée immédiatement avant et dans la même section que la ligne actuelle `index` du tableau. Si `index` vaut -1 ou est égal au nombre de lignes, la nouvelle ligne est ajoutée à la fin. De plus, lorsque le tableau est vide, la ligne est insérée dans un `TBODY` qui est créé et inséré dans le tableau. Une ligne de tableau ne peut pas être vide selon [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)].

```java
public Node InsertRow(int index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Le numéro de ligne où insérer une nouvelle ligne. Cet index commence à 0 et est relatif à l'ordre logique (et non à l'ordre du document) de toutes les lignes contenues dans le tableau. |

### Valeur de retour

La ligne nouvellement créée.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR : Levée si l'index spécifié est supérieur au nombre de lignes ou si l'index est un nombre négatif autre que -1. @version DOM Level 2 |

### Voir aussi

* class [Node](../../../com.aspose.html.dom/node/)
* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
