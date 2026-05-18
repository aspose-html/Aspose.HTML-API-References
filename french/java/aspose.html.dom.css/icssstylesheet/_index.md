---
title: "Interface ICSSStyleSheet"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.css.ICSSStyleSheet. L'interface CSSStyleSheet représente une feuille de style CSS unique et vous permet d'inspecter et de modifier la liste des règles contenues dans la feuille de style. Elle hérite des propriétés et méthodes de son parent IStyleSheet."
type: docs

url: /fr/java/com.aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

L'interface CSSStyleSheet représente une feuille de style CSS unique et vous permet d'inspecter et de modifier la liste des règles contenues dans la feuille de style. Elle hérite des propriétés et méthodes de son parent, [`IStyleSheet`](../istylesheet/).

Une feuille de style se compose d'une collection d'objets [`ICSSRule`](../icssrule/) représentant chacune des règles de la feuille de style. Les règles sont contenues dans une [`ICSSRuleList`](../icssrulelist/), qui peut être obtenue à partir de la propriété cssRules de la feuille de style.

Par exemple, une règle peut être un objet [`ICSSStyleRule`](../icssstylerule/) contenant un style tel que

```java
h1, h2 {   font-size: 16pt; }
```

Une autre règle peut être une règle at-rule telle que @import ou @media, etc.

```java
public interface ICSSStyleSheet : IStyleSheet
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icssstylesheet/cssrules/) La propriété en lecture seule cssRules de CSSStyleSheet renvoie une [`CSSRuleList`](../icssrulelist/) dynamique qui fournit une liste en temps réel, à jour, de chaque règle CSS qui compose la feuille de style. Chaque élément de la liste est un [`CSSRule`](../icssrule/) définissant une règle unique. |
| [getOwnerRule](../../com.aspose.html.dom.css/icssstylesheet/ownerrule/) La propriété en lecture seule ownerRule de CSSStyleSheet renvoie le [`CSSImportRule`](../icssimportrule/) correspondant à la règle at-rule @import qui a importé la feuille de style dans le document. Si la feuille de style n'a pas été importée dans le document à l'aide de @import, la valeur renvoyée est null. |

## Méthodes

| Nom | Description |
| --- | --- |
| [deleteRule](../../com.aspose.html.dom.css/icssstylesheet/deleterule/)(int) | La méthode `CSSStyleSheet` deleteRule() supprime une règle de l'objet feuille de style. |
| [insertRule](../../com.aspose.html.dom.css/icssstylesheet/insertrule/)(String, int) | La méthode CSSStyleSheet.insertRule() insère une nouvelle règle CSS dans la feuille de style actuelle, avec certaines restrictions. |

## Remarques

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Référence

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstylesheet](https://drafts.csswg.org/cssom/#cssstylesheet) – The CSSOM definition.

### Voir aussi

* interface [IStyleSheet](../istylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
