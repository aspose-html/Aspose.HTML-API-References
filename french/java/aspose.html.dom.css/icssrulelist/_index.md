---
title: "Interface ICSSRuleList"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.css.ICSSRuleList. Un CSSRuleList représente une collection ordonnée d'objets CSSRule en lecture seule"
type: docs

url: /fr/java/com.aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

Un CSSRuleList représente une collection ordonnée d'objets [`CSSRule`](../icssrule/) en lecture seule.

Bien que l'objet CSSRuleList soit en lecture seule et ne puisse pas être modifié directement, il est considéré comme un objet dynamique, car son contenu peut changer au fil du temps.

Pour modifier les règles sous‑jacentes renvoyées par les objets [`CSSRule`](../icssrule/), utilisez CSSStyleSheet.insertRule() et CSSStyleSheet.deleteRule(), qui sont des méthodes de [`CSSStyleSheet`](../icssstylesheet/).

```java
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssrulelist/item/) Utilisé pour récupérer une règle CSS via la méthode item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). L'ordre dans cette collection représente l'ordre des règles dans la feuille de style CSS. Si l'index est supérieur ou égal au nombre de règles dans la liste, cela renvoie null. |
| [getLength](../../com.aspose.html.dom.css/icssrulelist/length/) La propriété length de l'interface `CSSRuleList` renvoie le nombre d'objets [`CSSRule`](../icssrule/) dans la liste. |

### Voir aussi

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
