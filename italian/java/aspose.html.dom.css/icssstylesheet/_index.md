---
title: "Interfaccia ICSSStyleSheet"
second_title: "Aspose.HTML per Java Riferimento API"
description: "com.aspose.html.dom.css.ICSSStyleSheet interface. L'interfaccia CSSStyleSheet rappresenta un singolo foglio di stile CSS e consente di ispezionare e modificare l'elenco delle regole contenute nel foglio di stile. Eredita proprietà e metodi dal suo genitore IStyleSheet"
type: docs

url: /it/java/com.aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

L'interfaccia CSSStyleSheet rappresenta un singolo foglio di stile CSS e consente di ispezionare e modificare l'elenco delle regole contenute nel foglio di stile. Eredita proprietà e metodi dal suo genitore, [`IStyleSheet`](../istylesheet/).

Un foglio di stile è costituito da una raccolta di oggetti [`ICSSRule`](../icssrule/) che rappresentano ciascuna delle regole nel foglio di stile. Le regole sono contenute in una [`ICSSRuleList`](../icssrulelist/), che può essere ottenuta dalla proprietà cssRules del foglio di stile.

Ad esempio, una regola potrebbe essere un oggetto [`ICSSStyleRule`](../icssstylerule/) contenente uno stile come

```java
h1, h2 {   font-size: 16pt; }
```

Un'altra regola potrebbe essere una at-rule come @import o @media, e così via.

```java
public interface ICSSStyleSheet : IStyleSheet
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icssstylesheet/cssrules/) La proprietà di sola lettura cssRules di CSSStyleSheet restituisce una [`CSSRuleList`](../icssrulelist/) live che fornisce un elenco in tempo reale e aggiornato di ogni regola CSS che compone il foglio di stile. Ogni elemento dell'elenco è un [`CSSRule`](../icssrule/) che definisce una singola regola. |
| [getOwnerRule](../../com.aspose.html.dom.css/icssstylesheet/ownerrule/) La proprietà di sola lettura ownerRule di CSSStyleSheet restituisce il [`CSSImportRule`](../icssimportrule/) corrispondente alla at-rule @import che ha importato il foglio di stile nel documento. Se il foglio di stile non è stato importato nel documento usando @import, il valore restituito è null. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [deleteRule](../../com.aspose.html.dom.css/icssstylesheet/deleterule/)(int) | Il metodo `CSSStyleSheet` deleteRule() rimuove una regola dall'oggetto foglio di stile. |
| [insertRule](../../com.aspose.html.dom.css/icssstylesheet/insertrule/)(String, int) | Il metodo CSSStyleSheet.insertRule() inserisce una nuova regola CSS nel foglio di stile corrente, con alcune restrizioni. |

## Osservazioni

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Riferimento

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstylesheet](https://drafts.csswg.org/cssom/#cssstylesheet) – The CSSOM definition.

### Vedi anche

* interface [IStyleSheet](../istylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
