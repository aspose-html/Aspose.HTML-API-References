---
title: Class NamedNodeMap
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Collections.NamedNodeMap classe. Représente des collections dattributs accessibles par nom.
type: docs
weight: 40
url: /fr/net/aspose.html.collections/namednodemap/
---
## NamedNodeMap class

Représente des collections d'attributs accessibles par nom.

```csharp
public class NamedNodeMap : DOMObject, IDisposable, IEnumerable<Attr>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Item](../../aspose.html.collections/namednodemap/item/) { get; } | Renvoie l'index-ième élément de la carte. Si index est supérieur ou égal au nombre de nœuds dans cette carte, cela renvoie null. (2 indexers) |
| [Length](../../aspose.html.collections/namednodemap/length/) { get; } | Le nombre de nœuds dans cette carte. |

## Méthodes

| Nom | La description |
| --- | --- |
| [GetEnumerator](../../aspose.html.collections/namednodemap/getenumerator/)() | Renvoie un énumérateur qui parcourt la collection. |
| [GetNamedItem](../../aspose.html.collections/namednodemap/getnameditem/)(string) | Récupère un nœud spécifié par name. |
| [GetNamedItemNS](../../aspose.html.collections/namednodemap/getnameditemns/)(string, string) | Récupère un nœud spécifié par le nom local et l'URI de l'espace de noms. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |
| [RemoveNamedItem](../../aspose.html.collections/namednodemap/removenameditem/)(string) | Supprime un nœud spécifié par name. |
| [RemoveNamedItemNS](../../aspose.html.collections/namednodemap/removenameditemns/)(string, string) | Supprime un nœud spécifié par le nom local et l'URI de l'espace de noms. |
| [SetNamedItem](../../aspose.html.collections/namednodemap/setnameditem/)(Attr) | Ajoute un nœud à l'aide de son attribut nodeName. Si un nœud portant ce nom est déjà présent dans cette carte, il est remplacé par le nouveau. Remplacer un nœud par lui-même n'a aucun effet. |
| [SetNamedItemNS](../../aspose.html.collections/namednodemap/setnameditemns/)(Attr) | Ajoute un nœud en utilisant son namespaceURI et localName. Si un nœud avec cet URI d'espace de noms et ce nom local est déjà présent dans cette carte, il est remplacé par le nouveau. Remplacer un nœud par lui-même n'a aucun effet. |

### Voir également

* class [DOMObject](../../aspose.html.dom/domobject/)
* class [Attr](../../aspose.html.dom/attr/)
* espace de noms [Aspose.Html.Collections](../../aspose.html.collections/)
* Assemblée [Aspose.HTML](../../)


