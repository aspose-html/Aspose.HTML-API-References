---
title: Class CSSValue
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.Css.CSSValue classe. Représente une valeur simple ou complexe. Un objet CSSValue napparaît que dans le contexte dune propriété CSS.
type: docs
weight: 340
url: /fr/net/aspose.html.dom.css/cssvalue/
---
## CSSValue class

Représente une valeur simple ou complexe. Un objet CSSValue n'apparaît que dans le contexte d'une propriété CSS.

```csharp
public abstract class CSSValue : DOMObject
```

## Propriétés

| Nom | La description |
| --- | --- |
| abstract [CSSText](../../aspose.html.dom.css/cssvalue/csstext/) { get; set; } | Une représentation sous forme de chaîne de la valeur actuelle. |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | Un code définissant le type de la valeur. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(object) | Détermine si la valeur spécifiéeObject est égal à cette instance. |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | Renvoie un code de hachage pour cette instance. |
| override [GetPlatformType](../../aspose.html.dom.css/cssvalue/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | Renvoie unString qui représente cette instance. |
| [operator ==](../../aspose.html.dom.css/cssvalue/op_equality/) | Implémente l'opérateur ==. |
| [operator !=](../../aspose.html.dom.css/cssvalue/op_inequality/) | Implémente l'opérateur !=. |

## Des champs

| Nom | La description |
| --- | --- |
| const [CSS_CUSTOM](../../aspose.html.dom.css/cssvalue/css_custom/) | La valeur est une valeur personnalisée. |
| const [CSS_INHERIT](../../aspose.html.dom.css/cssvalue/css_inherit/) | La valeur est héritée et le cssText contient "inherit". |
| const [CSS_PRIMITIVE_VALUE](../../aspose.html.dom.css/cssvalue/css_primitive_value/) | La valeur est une valeur primitive et une instance de l'interface CSSPrimitiveValue peut être obtenue en utilisant des méthodes de transtypage spécifiques à la liaison sur cette instance de l'interface CSSValue. |
| const [CSS_VALUE_LIST](../../aspose.html.dom.css/cssvalue/css_value_list/) | La valeur est une liste CSSValue et une instance de l'interface CSSValueList peut être obtenue en utilisant des méthodes de transtypage spécifiques à la liaison sur cette instance de l'interface CSSValue. |

### Voir également

* class [DOMObject](../../aspose.html.dom/domobject/)
* espace de noms [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* Assemblée [Aspose.HTML](../../)


