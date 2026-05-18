---
title: "Interface IXPathResult"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.xpath.IXPathResult. L'interface XPathResult représente le résultat de l'évaluation d'une expression XPath 1.0 dans le contexte d'un nœud particulier. Étant donné que l'évaluation d'une expression XPath peut produire divers types de résultats, cet objet permet de découvrir et de manipuler le type et la valeur du résultat."
type: docs

url: /fr/java/com.aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

L’interface `XPathResult` représente le résultat de l’évaluation d’une expression XPath 1.0 dans le contexte d’un nœud particulier. Étant donné que l’évaluation d’une expression XPath peut produire divers types de résultats, cet objet permet de découvrir et de manipuler le type et la valeur du résultat.

```java
public interface IXPathResult
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getBooleanValue](../../com.aspose.html.dom.xpath/ixpathresult/booleanvalue/) La valeur de ce résultat booléen. |
| [getInvalidIteratorState](../../com.aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) Signale que l'itérateur est devenu invalide. Vrai si `resultType` est de type `UnorderedNodeIterator` ou `OrderedNodeIterator` et que le document a été modifié depuis que ce résultat a été retourné. |
| [getNumberValue](../../com.aspose.html.dom.xpath/ixpathresult/numbervalue/) La valeur de ce résultat numérique. |
| [getResultType](../../com.aspose.html.dom.xpath/ixpathresult/resulttype/) Un code représentant le type de ce résultat, tel que défini par l'énumération http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult[`XPathResultType`](../xpathresulttype/) enum. |
| [getSingleNodeValue](../../com.aspose.html.dom.xpath/ixpathresult/singlenodevalue/) La valeur de ce résultat de nœud unique, qui peut être `null`. |
| [getSnapshotLength](../../com.aspose.html.dom.xpath/ixpathresult/snapshotlength/) Le nombre de nœuds dans l'instantané du résultat. Les valeurs valides pour les indices snapshotItem sont de `0` à `snapshotLength-1` inclus. |
| [getStringValue](../../com.aspose.html.dom.xpath/ixpathresult/Stringvalue/) La valeur de ce résultat de chaîne. |

## Méthodes

| Nom | Description |
| --- | --- |
| [iterateNext](../../com.aspose.html.dom.xpath/ixpathresult/iteratenext/)() | Itère et renvoie le nœud suivant de l'ensemble de nœuds ou `null` s'il n'y a plus de nœuds. |
| [snapshotItem](../../com.aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | Renvoie l'élément `index`e de la collection d'instantanés. Si `index` est supérieur ou égal au nombre de nœuds dans la liste, cette méthode renvoie `null`. Contrairement au résultat de l'itérateur, l'instantané ne devient pas invalide, mais il peut ne pas correspondre au document actuel s'il est modifié. |

### Voir aussi

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
