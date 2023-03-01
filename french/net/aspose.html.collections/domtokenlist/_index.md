---
title: Class DOMTokenList
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Collections.DOMTokenList classe. La classe DOMTokenList représente un ensemble de jetons séparés par des espaces. Il est indexé en commençant par 0 comme pour les objets JavaScript Array. DOMTokenList est toujours sensible à la casse.
type: docs
weight: 20
url: /fr/net/aspose.html.collections/domtokenlist/
---
## DOMTokenList class

La classe DOMTokenList représente un ensemble de jetons séparés par des espaces. Il est indexé en commençant par 0 comme pour les objets JavaScript Array. DOMTokenList est toujours sensible à la casse.

```csharp
public class DOMTokenList : DOMObject, IEnumerable<string>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Item](../../aspose.html.collections/domtokenlist/item/) { get; } | Renvoie l'élément de la liste par son index, ou null si l'index est supérieur ou égal à la longueur de la liste. |
| [Length](../../aspose.html.collections/domtokenlist/length/) { get; } | Renvoie un ulong qui représente le nombre de jetons stockés dans cette liste. |
| [Value](../../aspose.html.collections/domtokenlist/value/) { get; set; } | Obtient ou définit la valeur d'un attribut correspondant. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Add](../../aspose.html.collections/domtokenlist/add/)(params string[]) | Ajoute le ou les jetons spécifiés à la liste. |
| [Contains](../../aspose.html.collections/domtokenlist/contains/)(string) | Renvoie vrai si la liste contient le jeton donné, sinon faux. |
| [GetEnumerator](../../aspose.html.collections/domtokenlist/getenumerator/)() | Renvoie un énumérateur qui parcourt la collection. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |
| [Remove](../../aspose.html.collections/domtokenlist/remove/)(params string[]) | Supprime le ou les jetons spécifiés de la liste. |
| [Replace](../../aspose.html.collections/domtokenlist/replace/)(string, string) | Remplace un jeton existant par un nouveau jeton. Ne fait rien si le premier jeton n'existe pas. |
| [Supports](../../aspose.html.collections/domtokenlist/supports/)(string) | Renvoie vrai si un jeton donné se trouve dans les jetons pris en charge par l'attribut associé. |
| [Toggle](../../aspose.html.collections/domtokenlist/toggle/#toggle)(string) | Supprime le jeton de la liste s'il existe, ou ajoute le jeton à la liste si ce n'est pas le cas. |
| [Toggle](../../aspose.html.collections/domtokenlist/toggle/#toggle_1)(string, bool?) | Supprime le jeton de la liste s'il existe, ou ajoute le jeton à la liste si ce n'est pas le cas. |

### Voir également

* class [DOMObject](../../aspose.html.dom/domobject/)
* espace de noms [Aspose.Html.Collections](../../aspose.html.collections/)
* Assemblée [Aspose.HTML](../../)


