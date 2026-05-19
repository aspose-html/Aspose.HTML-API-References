---
title: "Interfaccia ICSSRuleList"
second_title: "Riferimento API Aspose.HTML per Java"
description: "interfaccia com.aspose.html.dom.css.ICSSRuleList. Un CSSRuleList rappresenta una collezione ordinata di oggetti CSSRule read-only."
type: docs

url: /it/java/com.aspose.html.dom.css/icssrulelist/
---
## ICSSRuleList interface

Un CSSRuleList rappresenta una collezione ordinata di oggetti read-only [`CSSRule`](../icssrule/).

Mentre l'oggetto CSSRuleList è read-only e non può essere modificato direttamente, è considerato un oggetto live, poiché il contenuto può cambiare nel tempo.

Per modificare le regole sottostanti restituite dagli oggetti [`CSSRule`](../icssrule/), usa CSSStyleSheet.insertRule() e CSSStyleSheet.deleteRule(), che sono metodi di [`CSSStyleSheet`](../icssstylesheet/).

```java
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssrulelist/item/) Usato per recuperare una regola CSS mediante il metodo item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). L'ordine in questa collezione rappresenta l'ordine delle regole nel foglio di stile CSS. Se l'indice è maggiore o uguale al numero di regole nella lista, questo restituisce null. |
| [getLength](../../com.aspose.html.dom.css/icssrulelist/length/) La proprietà length dell'interfaccia `CSSRuleList` restituisce il numero di oggetti [`CSSRule`](../icssrule/) nella lista. |

### Vedi anche

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
