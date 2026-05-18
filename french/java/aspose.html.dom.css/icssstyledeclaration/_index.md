---
title: "Interface ICSSStyleDeclaration"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.css.ICSSStyleDeclaration. L'interface CSSStyleDeclaration représente un objet qui est un bloc de déclaration CSS et expose des informations de style ainsi que diverses méthodes et propriétés liées au style."
type: docs

url: /fr/java/com.aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

L'interface CSSStyleDeclaration représente un objet qui est un bloc de déclaration CSS, et expose des informations de style ainsi que diverses méthodes et propriétés liées au style.

Un objet CSSStyleDeclaration peut être exposé à l'aide de trois API différentes :

Via HTMLElement.style, qui gère les styles en ligne d'un seul élément. Via l'API [`CSSStyleSheet`](../icssstylesheet/). Par exemple, document.styleSheets[0].cssRules[0].style renvoie un objet `CSSStyleDeclaration` sur la première règle CSS du premier feuille de style du document. Via Window.getComputedStyle(), qui expose l'objet `CSSStyleDeclaration` en tant qu'interface en lecture seule.

```java
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<String>
```

## Propriétés

| Nom | Description |
| --- | --- |
[getCSSText]
[setCSSText] The parsable textual representation of the declaration block (excluding the surrounding curly braces). Setting this attribute will result in the parsing of the new value and resetting of all the properties in the declaration block including the removal or addition of properties. |
| [getItem](../../com.aspose.html.dom.css/icssstyledeclaration/item/) Utilisé pour récupérer les propriétés qui ont été explicitement définies dans ce bloc de déclaration. L'ordre des propriétés récupérées avec cette méthode n'a pas besoin d'être celui dans lequel elles ont été définies. Cette méthode peut être utilisée pour parcourir toutes les propriétés de ce bloc de déclaration. |
| [getLength](../../com.aspose.html.dom.css/icssstyledeclaration/length/) La propriété en lecture seule renvoie un nombre entier de propriétés qui ont été explicitement définies dans ce bloc de déclaration CSS. L'intervalle des indices valides est de 0 à length-1 inclus. |
| [getParentRule](../../com.aspose.html.dom.css/icssstyledeclaration/parentrule/) La propriété en lecture seule CSSStyleDeclaration.parentRule renvoie un CSSRule qui est le parent de ce bloc de style, par ex. un [`CSSStyleRule`](../icssstylerule/) représentant le style d'un sélecteur CSS. |

## Méthodes

| Nom | Description |
| --- | --- |
| [getPropertyCSSValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(String) | Utilisé pour récupérer la représentation objet de la valeur d'une propriété CSS si elle a été explicitement définie dans ce bloc de déclaration. Cette méthode renvoie null si la propriété est une propriété raccourcie. Les valeurs des propriétés raccourcies ne peuvent être accédées et modifiées que sous forme de chaînes, en utilisant les méthodes getPropertyValue et setProperty. |
| [getPropertyPriority](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(String) | Utilisé pour récupérer la priorité d'une propriété CSS (par ex. le qualificatif "important") si la propriété a été explicitement définie dans ce bloc de déclaration. |
| [getPropertyValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(String) | L'interface de méthode CSSStyleDeclaration.getPropertyValue() renvoie une chaîne contenant la valeur d'une propriété CSS spécifiée. |
| [removeProperty](../../com.aspose.html.dom.css/icssstyledeclaration/removeproperty/)(String) | L'interface de méthode CSSStyleDeclaration.removeProperty() supprime une propriété d'un objet de déclaration de style CSS. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(String, String) | L'interface de méthode CSSStyleDeclaration.setProperty() est utilisée pour définir la valeur d'une propriété avec la priorité par défaut dans ce bloc de déclaration. La priorité par défaut n'est pas "important", c'est‑à‑dire String.Empty. |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(String, String, String) | L'interface de méthode CSSStyleDeclaration.setProperty() est utilisée pour définir la valeur d'une propriété avec la priorité par défaut dans ce bloc de déclaration. La priorité par défaut n'est pas "important", c'est‑à‑dire String.Empty. |

## Remarques

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Référence

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstyledeclaration](https://drafts.csswg.org/cssom/#cssstyledeclaration) – The CSSOM definition.

### Voir aussi

* interface [ICSS2Properties](../icss2properties/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
