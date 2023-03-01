---
title: Interface ICSSCharsetRule
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.Css.ICSSCharsetRule interface. Linterface CSSCharsetRule représente une règle charset dans une feuille de style CSS. La valeur de lattribut encoding naffecte pas lencodage des données textuelles dans les objets DOM  cet encodage est toujours UTF16. Après le chargement dune feuille de style la valeur de lattribut encoding est la valeur trouvée dans la règle charset. Sil ny avait pas de charset dans le document dorigine aucun CSSCharsetRule nest créé. La valeur de lattribut dencodage peut également être utilisée comme indice pour lencodage utilisé lors de la sérialisation de la feuille de style.
type: docs
weight: 380
url: /fr/net/aspose.html.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

L'interface CSSCharsetRule représente une règle @charset dans une feuille de style CSS. La valeur de l'attribut encoding n'affecte pas l'encodage des données textuelles dans les objets DOM ; cet encodage est toujours UTF-16. Après le chargement d'une feuille de style, la valeur de l'attribut encoding est la valeur trouvée dans la règle @charset. S'il n'y avait pas de @charset dans le document d'origine, aucun CSSCharsetRule n'est créé. La valeur de l'attribut d'encodage peut également être utilisée comme indice pour l'encodage utilisé lors de la sérialisation de la feuille de style.

```csharp
public interface ICSSCharsetRule : ICSSRule
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Encoding](../../aspose.html.dom.css/icsscharsetrule/encoding/) { get; set; } | Les informations de codage utilisées dans cette règle @charset. |

### Voir également

* interface [ICSSRule](../icssrule/)
* espace de noms [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* Assemblée [Aspose.HTML](../../)


