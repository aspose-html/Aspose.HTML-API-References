---
title: "Classe CSSValue"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.dom.css.CSSValue. Représente une valeur simple ou complexe. Un objet CSSValue n'apparaît que dans le contexte d'une propriété CSS."
type: docs

url: /fr/java/com.aspose.html.dom.css/cssvalue/
---
## CSSValue class

Représente une valeur simple ou complexe. Un objet CSSValue n'apparaît que dans le contexte d'une propriété CSS.

```java
public abstract class CSSValue : DOMObject
```

## Propriétés

| Nom | Description |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | La propriété cssText de l'interface `CSSValue` représente la valeur actuelle calculée de la propriété CSS. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) Un code définissant le type de la valeur. |

## Méthodes

| Nom | Description |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Détermine si l'objet spécifié est égal à cette instance. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Renvoie un code de hachage pour cette instance. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | Cette méthode est utilisée pour récupérer le type d'objet ECMAScript. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Renvoie une chaîne qui représente cette instance. |
| [operator ==](../../com.aspose.html.dom.css/cssvalue/op_equality/) |  |
| [operator !=](../../com.aspose.html.dom.css/cssvalue/op_inequality/) |  |

## Champs

| Nom | Description |
| --- | --- |
| const [CSS_CUSTOM](../../com.aspose.html.dom.css/cssvalue/css_custom/) | La valeur est une valeur personnalisée. |
| const [CSS_INHERIT](../../com.aspose.html.dom.css/cssvalue/css_inherit/) | La valeur est héritée et le cssText contient "inherit". |
| const [CSS_PRIMITIVE_VALUE](../../com.aspose.html.dom.css/cssvalue/css_primitive_value/) | La valeur est une valeur primitive et une instance de l'interface CSSPrimitiveValue peut être obtenue en utilisant des méthodes de cast spécifiques au binding sur cette instance de l'interface CSSValue. |
| const [CSS_VALUE_LIST](../../com.aspose.html.dom.css/cssvalue/css_value_list/) | La valeur est une liste CSSValue et une instance de l'interface CSSValueList peut être obtenue en utilisant des méthodes de conversion spécifiques à la liaison sur cette instance de l'interface CSSValue. |

### Voir aussi

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
