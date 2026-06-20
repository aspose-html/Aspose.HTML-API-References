---
title: "ICSSStyleSheet.InsertRule"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode ICSSStyleSheet. La méthode CSSStyleSheet.insertRule insère une nouvelle règle CSS dans la feuille de style actuelle avec certaines restrictions"
type: docs

url: /fr/java/com.aspose.html.dom.css/icssstylesheet/insertrule/
---
## ICSSStyleSheet.InsertRule method

La méthode CSSStyleSheet.insertRule() insère une nouvelle règle CSS dans la feuille de style actuelle, avec certaines restrictions.

Remarque : Bien que insertRule() soit exclusivement une méthode de [`CSSStyleSheet`](../), elle insère en réalité la règle dans CSSStyleSheet.cssRules — son [`CSSRuleList`](../../icssrulelist/) interne.

```java
public long InsertRule(String rule, int index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| règle | String | Une chaîne contenant la règle à insérer. Ce que la règle insérée doit contenir dépend de son type : |
| index | Int32 | Un entier positif inférieur ou égal à stylesheet.cssRules.length, représentant la position de la règle nouvellement insérée dans CSSStyleSheet.cssRules. La valeur par défaut est 0. |

### Valeur de retour

L'index de la règle nouvellement insérée dans la liste des règles de la feuille de style.

## Remarques

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Référence

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-insertrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-insertrule) – The CSSOM definition.

### Voir aussi

* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
