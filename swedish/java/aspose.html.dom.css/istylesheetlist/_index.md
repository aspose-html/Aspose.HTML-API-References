---
title: "IStyleSheetList gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.css.IStyleSheetList interface. StyleSheetList‑gränssnittet representerar en lista av CSSStyleSheet‑objekt. En instans av detta objekt kan returneras av Document.styleSheets."
type: docs

url: /sv/java/com.aspose.html.dom.css/istylesheetlist/
---
## IStyleSheetList interface

StyleSheetList‑gränssnittet representerar en lista av [`CSSStyleSheet`](../icssstylesheet/)‑objekt. En instans av detta objekt kan returneras av [`Document.styleSheets`](../../com.aspose.html.dom/document/stylesheets/).

Objektets stödda egenskapsindex är siffrorna i intervallet noll till ett mindre än antalet CSS‑stilark som representeras av samlingen. Om det inte finns några sådana CSS‑stilark finns det inga stödda egenskapsindex.

```java
public interface IStyleSheetList : IEnumerable<ICSSStyleSheet>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/istylesheetlist/item/) item(index)‑metoden måste returnera det indexte [`CSS style sheet`](../icssstylesheet/) i samlingen. Om det inte finns något objekt på det indexet måste metoden returnera null. |
| [getLength](../../com.aspose.html.dom.css/istylesheetlist/length/) length‑attributet måste returnera antalet CSS‑stilark som representeras av samlingen. Intervallet för giltiga understilark‑index är 0 till length‑1 inklusive. |

## Anmärkningar

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referens

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # stylesheetlist](https://drafts.csswg.org/cssom/#stylesheetlist) – The CSSOM definition.

### Se även

* interface [ICSSStyleSheet](../icssstylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
