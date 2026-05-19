---
title: "Interfaccia ICSSRule"
second_title: "Riferimento API Aspose.HTML per Java"
description: "interfaccia com.aspose.html.dom.css.ICSSRule. L'interfaccia CSSRule è l'interfaccia base astratta per qualsiasi tipo di dichiarazione CSS. Include sia insiemi di regole che at-rule. Un'implementazione dovrebbe preservare tutte le regole specificate in un foglio di stile CSS anche se la regola non è riconosciuta dal parser. Le regole non riconosciute sono rappresentate usando l'interfaccia."
type: docs

url: /it/java/com.aspose.html.dom.css/icssrule/
---
## ICSSRule interface

L'interfaccia CSSRule è l'interfaccia base astratta per qualsiasi tipo di dichiarazione CSS. Include sia set di regole che at-rule. Un'implementazione dovrebbe preservare tutte le regole specificate in un foglio di stile CSS, anche se la regola non è riconosciuta dal parser. Le regole non riconosciute sono rappresentate tramite l'interfaccia.

```java
public interface ICSSRule
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
[getCSSText]
[setCSSText] The cssText property of the `CSSRule` interface returns the actual text of a [`CSSStyleSheet`](../icssstylesheet/) style-rule. |
| [getParentRule](../../com.aspose.html.dom.css/icssrule/parentrule/) Se questa regola è contenuta all'interno di un'altra regola (ad esempio una regola di stile all'interno di un blocco @media), questa è la regola contenente. Se questa regola non è annidata all'interno di altre regole, restituisce null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/icssrule/parentstylesheet/) La proprietà parentStyleSheet dell'interfaccia `CSSRule` restituisce l'oggetto [`StyleSheet`](../istylesheet/) in cui è definita la regola corrente. |
| [getType](../../com.aspose.html.dom.css/icssrule/type/) Il tipo della regola, come definito [CSSOM # dom-cssrule-type](https://drafts.csswg.org/cssom/#dom-cssrule-type). Si prevede che i metodi di casting specifici per il binding possano essere usati per effettuare il downcast da un'istanza dell'interfaccia CSSRule all'interfaccia derivata specifica implicata dal tipo. |

### Vedi anche

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
