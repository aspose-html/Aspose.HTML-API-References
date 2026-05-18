---
title: "IStyleSheetList‑Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.css.IStyleSheetList‑Schnittstelle. Die StyleSheetList‑Schnittstelle repräsentiert eine Liste von CSSStyleSheet‑Objekten. Eine Instanz dieses Objekts kann über Document.styleSheets zurückgegeben werden."
type: docs

url: /de/java/com.aspose.html.dom.css/istylesheetlist/
---
## IStyleSheetList interface

Die StyleSheetList‑Schnittstelle stellt eine Liste von [`CSSStyleSheet`](../icssstylesheet/)‑Objekten dar. Eine Instanz dieses Objekts kann über [`Document.styleSheets`](../../com.aspose.html.dom/document/stylesheets/) zurückgegeben werden.

Die vom Objekt unterstützten Eigenschaftsindizes sind die Zahlen im Bereich von null bis eins weniger als die Anzahl der von der Sammlung repräsentierten CSS‑Stylesheets. Gibt es keine solchen CSS‑Stylesheets, existieren keine unterstützten Eigenschaftsindizes.

```java
public interface IStyleSheetList : IEnumerable<ICSSStyleSheet>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/istylesheetlist/item/) Die Methode item(index) muss das index‑te [`CSS style sheet`](../icssstylesheet/) in der Sammlung zurückgeben. Gibt es kein index‑tes Objekt in der Sammlung, muss die Methode null zurückgeben. |
| [getLength](../../com.aspose.html.dom.css/istylesheetlist/length/) Das Attribut length muss die Anzahl der von der Sammlung repräsentierten CSS‑Stylesheets zurückgeben. Der gültige Bereich für Kind‑Stylesheet‑Indizes ist 0 bis length‑1 inklusive. |

## Hinweise

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referenz

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # stylesheetlist](https://drafts.csswg.org/cssom/#stylesheetlist) – The CSSOM definition.

### Siehe auch

* interface [ICSSStyleSheet](../icssstylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
