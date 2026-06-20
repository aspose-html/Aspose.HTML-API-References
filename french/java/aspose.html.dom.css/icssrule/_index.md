---
title: "Interface ICSSRule"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.css.ICSSRule. L'interface CSSRule est l'interface de base abstraite pour tout type d'instruction CSS. Cela inclut les ensembles de règles et les at-rules. Une implémentation doit préserver toutes les règles spécifiées dans une feuille de style CSS même si la règle n'est pas reconnue par l'analyseur. Les règles non reconnues sont représentées à l'aide de l'interface."
type: docs

url: /fr/java/com.aspose.html.dom.css/icssrule/
---
## ICSSRule interface

L'interface CSSRule est l'interface de base abstraite pour tout type d'instruction CSS. Cela inclut à la fois les ensembles de règles et les règles at-rules. Une implémentation doit préserver toutes les règles spécifiées dans une feuille de style CSS, même si la règle n'est pas reconnue par l'analyseur. Les règles non reconnues sont représentées à l'aide de l'interface.

```java
public interface ICSSRule
```

## Propriétés

| Nom | Description |
| --- | --- |
[getCSSText]
[setCSSText] The cssText property of the `CSSRule` interface returns the actual text of a [`CSSStyleSheet`](../icssstylesheet/) style-rule. |
| [getParentRule](../../com.aspose.html.dom.css/icssrule/parentrule/) Si cette règle est contenue à l'intérieur d'une autre règle (par ex. une règle de style à l'intérieur d'un bloc @media), il s'agit de la règle contenant. Si cette règle n'est pas imbriquée dans d'autres règles, elle renvoie null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/icssrule/parentstylesheet/) La propriété parentStyleSheet de l'interface `CSSRule` renvoie l'objet [`StyleSheet`](../istylesheet/) dans lequel la règle actuelle est définie. |
| [getType](../../com.aspose.html.dom.css/icssrule/type/) Le type de la règle, tel que défini [CSSOM # dom-cssrule-type](https://drafts.csswg.org/cssom/#dom-cssrule-type). On s'attend à ce que des méthodes de cast spécifiques aux liaisons puissent être utilisées pour descendre d'une instance de l'interface CSSRule vers l'interface dérivée spécifique implicite du type. |

### Voir aussi

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
