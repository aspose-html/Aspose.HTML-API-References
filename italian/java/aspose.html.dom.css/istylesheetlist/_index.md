---
title: "Interfaccia IStyleSheetList"
second_title: "Aspose.HTML per Java Riferimento API"
description: "com.aspose.html.dom.css.IStyleSheetList interface. L'interfaccia StyleSheetList rappresenta un elenco di oggetti CSSStyleSheet. Un'istanza di questo oggetto può essere restituita da Document.styleSheets."
type: docs

url: /it/java/com.aspose.html.dom.css/istylesheetlist/
---
## IStyleSheetList interface

L'interfaccia StyleSheetList rappresenta un elenco di oggetti [`CSSStyleSheet`](../icssstylesheet/). Un'istanza di questo oggetto può essere restituita da [`Document.styleSheets`](../../com.aspose.html.dom/document/stylesheets/).

Gli indici delle proprietà supportate dall'oggetto sono i numeri nell'intervallo da zero a uno meno del numero di fogli di stile CSS rappresentati dalla collezione. Se non esistono tali fogli di stile CSS, non ci sono indici di proprietà supportati.

```java
public interface IStyleSheetList : IEnumerable<ICSSStyleSheet>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/istylesheetlist/item/) Il metodo item(index) deve restituire il [`CSS style sheet`](../icssstylesheet/) all'indice specificato nella collezione. Se non esiste alcun oggetto all'indice specificato nella collezione, il metodo deve restituire null. |
| [getLength](../../com.aspose.html.dom.css/istylesheetlist/length/) L'attributo length deve restituire il numero di fogli di stile CSS rappresentati dalla collezione. L'intervallo degli indici dei fogli di stile figli validi è da 0 a length-1 inclusi. |

## Osservazioni

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Riferimento

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # stylesheetlist](https://drafts.csswg.org/cssom/#stylesheetlist) – The CSSOM definition.

### Vedi anche

* interface [ICSSStyleSheet](../icssstylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
