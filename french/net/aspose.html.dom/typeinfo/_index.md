---
title: Class TypeInfo
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.TypeInfo classe. Le TypeInfo représente un type référencé à partir des nœuds Element ou Attr spécifié dans les schémas associés au document.
type: docs
weight: 2530
url: /fr/net/aspose.html.dom/typeinfo/
---
## TypeInfo class

Le TypeInfo représente un type référencé à partir des nœuds Element ou Attr, spécifié dans les schémas associés au document.

```csharp
public class TypeInfo : DOMObject
```

## Propriétés

| Nom | La description |
| --- | --- |
| [TypeName](../../aspose.html.dom/typeinfo/typename/) { get; } | Le nom d'un type déclaré pour l'élément ou l'attribut associé, ou null si inconnu. |
| [TypeNamespace](../../aspose.html.dom/typeinfo/typenamespace/) { get; } | Obtient l'espace de noms de type. L'espace de noms du type déclaré pour l'élément ou l'attribut associé ou null si l'élément n'a pas de déclaration ou si aucune information d'espace de noms n'est disponible. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |
| [IsDerivedFrom](../../aspose.html.dom/typeinfo/isderivedfrom/)(string, string, ulong) | Cette méthode renvoie s'il existe une dérivation entre la définition du type de référence, c'est-à-dire le TypeInfo sur lequel la méthode est appelée, et l'autre définition de type, c'est-à-dire celle passée en paramètre. |

## Des champs

| Nom | La description |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.html.dom/typeinfo/derivation_extension/) | Si le schéma du document est un schéma XML [XML Schema Part 1], cette constante représente la dérivation par extension. |
| const [DERIVATION_LIST](../../aspose.html.dom/typeinfo/derivation_list/) | Si le schéma du document est un schéma XML [XML Schema Part 1], cette constante représente la liste. |
| const [DERIVATION_RESTRICTION](../../aspose.html.dom/typeinfo/derivation_restriction/) | Si le schéma du document est un XML Schema [XML Schema Part 1], cette constante représente la dérivation par restriction s'il s'agit de types complexes, ou une restriction s'il s'agit de types simples. |
| const [DERIVATION_UNION](../../aspose.html.dom/typeinfo/derivation_union/) | Si le schéma du document est un schéma XML [XML Schema Part 1], cette constante représente l'union si des types simples sont impliqués. |

### Voir également

* class [DOMObject](../domobject/)
* espace de noms [Aspose.Html.Dom](../../aspose.html.dom/)
* Assemblée [Aspose.HTML](../../)


