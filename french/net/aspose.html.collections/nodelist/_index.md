---
title: Class NodeList
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Collections.NodeList classe. La NodeList fournit labstraction dune collection ordonnée de nœuds sans définir ni contraindre la façon dont cette collection est implémentée.
type: docs
weight: 50
url: /fr/net/aspose.html.collections/nodelist/
---
## NodeList class

La NodeList fournit l'abstraction d'une collection ordonnée de nœuds, sans définir ni contraindre la façon dont cette collection est implémentée.

```csharp
public abstract class NodeList : DOMObject, IEnumerable<Node>
```

## Propriétés

| Nom | La description |
| --- | --- |
| abstract [Item](../../aspose.html.collections/nodelist/item/) { get; } | La méthode renvoie l'élément d'index de la collection. Si index est supérieur ou égal au nombre de nœuds dans la liste, cela renvoie null. |
| abstract [Length](../../aspose.html.collections/nodelist/length/) { get; } | Le nombre de nœuds dans la liste. |

## Méthodes

| Nom | La description |
| --- | --- |
| abstract [GetEnumerator](../../aspose.html.collections/nodelist/getenumerator/)() | Renvoie un énumérateur qui parcourt la collection. |
| override [GetPlatformType](../../aspose.html.collections/nodelist/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |

### Voir également

* class [DOMObject](../../aspose.html.dom/domobject/)
* class [Node](../../aspose.html.dom/node/)
* espace de noms [Aspose.Html.Collections](../../aspose.html.collections/)
* Assemblée [Aspose.HTML](../../)


