---
title: Interface ICSSRuleList
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.Css.ICSSRuleList interface. Linterface CSSRuleList fournit labstraction dune collection ordonnée de règles CSS.
type: docs
weight: 480
url: /fr/net/aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

L'interface CSSRuleList fournit l'abstraction d'une collection ordonnée de règles CSS.

```csharp
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Item](../../aspose.html.dom.css/icssrulelist/item/) { get; } | Utilisé pour récupérer une règle CSS par la méthode item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). L'ordre dans cette collection représente l'ordre des règles dans la feuille de style CSS. Si index est supérieur ou égal au nombre de règles dans la liste, cela renvoie null. |
| [Length](../../aspose.html.dom.css/icssrulelist/length/) { get; } | Le nombre de CSSRules dans la liste. La plage d'indices de règle enfant valides est de 0 à longueur-1 inclus. |

### Voir également

* interface [ICSSRule](../icssrule/)
* espace de noms [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* Assemblée [Aspose.HTML](../../)


