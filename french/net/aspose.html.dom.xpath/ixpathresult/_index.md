---
title: Interface IXPathResult
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.XPath.IXPathResult interface. LeXPathResult interface représente le résultat de lévaluation dune expression XPath 1.0 dans le contexte dun nœud particulier. Étant donné que lévaluation dune expression XPath peut aboutir à différents types de résultats cet objet permet de découvrir et de manipuler le type et la valeur du résultat.
type: docs
weight: 2600
url: /fr/net/aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

Le`XPathResult` interface représente le résultat de l'évaluation d'une expression XPath 1.0 dans le contexte d'un nœud particulier. Étant donné que l'évaluation d'une expression XPath peut aboutir à différents types de résultats, cet objet permet de découvrir et de manipuler le type et la valeur du résultat.

```csharp
public interface IXPathResult
```

## Propriétés

| Nom | La description |
| --- | --- |
| [BooleanValue](../../aspose.html.dom.xpath/ixpathresult/booleanvalue/) { get; } | La valeur de ce résultat booléen. |
| [InvalidIteratorState](../../aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | Signifie que l'itérateur est devenu invalide. Vrai si`type de résultat` est`UnorderedNodeIteratorUnorderedNodeIterator` taper ou`OrderedNodeIteratorOrderedNodeIterator` tapez et le document a été modifié depuis que ce résultat a été renvoyé. |
| [NumberValue](../../aspose.html.dom.xpath/ixpathresult/numbervalue/) { get; } | La valeur de ce résultat numérique. |
| [ResultType](../../aspose.html.dom.xpath/ixpathresult/resulttype/) { get; } | Un code représentant le type de ce résultat, tel que défini par le http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult [`XPathResultType`](../xpathresulttype/) enum. |
| [SingleNodeValue](../../aspose.html.dom.xpath/ixpathresult/singlenodevalue/) { get; } | La valeur de ce résultat de nœud unique, qui peut être`nul` . |
| [SnapshotLength](../../aspose.html.dom.xpath/ixpathresult/snapshotlength/) { get; } | Le nombre de nœuds dans l'instantané de résultat. Les valeurs valides pour les indices snapshotItem sont`0` pour`snapshotLength-1` inclus. |
| [StringValue](../../aspose.html.dom.xpath/ixpathresult/stringvalue/) { get; } | La valeur de ce résultat de chaîne. |

## Méthodes

| Nom | La description |
| --- | --- |
| [IterateNext](../../aspose.html.dom.xpath/ixpathresult/iteratenext/)() | Itère et renvoie le nœud suivant à partir de l'ensemble de nœuds ou`nul` s'il n'y a plus de nœuds. |
| [SnapshotItem](../../aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | Renvoie le`indice` ème élément de la collection d'instantanés. Si`indice`est supérieur à ou égal au nombre de nœuds de la liste, cette méthode renvoie`nul` . Contrairement au résultat de l'itérateur , l'instantané ne devient pas invalide, mais peut ne pas correspondre au document actuel s'il est muté. |

### Voir également

* espace de noms [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* Assemblée [Aspose.HTML](../../)


