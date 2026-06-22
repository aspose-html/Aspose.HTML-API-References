---
title: "IStyleSheetList Interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.css.IStyleSheetList interface. De StyleSheetList‑interface vertegenwoordigt een lijst van CSSStyleSheet‑objecten. Een instantie van dit object kan worden verkregen via Document.styleSheets."
type: docs

url: /nl/java/com.aspose.html.dom.css/istylesheetlist/
---
## IStyleSheetList interface

De StyleSheetList‑interface vertegenwoordigt een lijst van [`CSSStyleSheet`](../icssstylesheet/) objecten. Een instantie van dit object kan worden verkregen via [`Document.styleSheets`](../../com.aspose.html.dom/document/stylesheets/).

De ondersteunde eigenschapsindices van het object zijn de getallen in het bereik van nul tot één minder dan het aantal CSS‑stijlbladen dat door de collectie wordt vertegenwoordigd. Als er geen dergelijke CSS‑stijlbladen zijn, zijn er geen ondersteunde eigenschapsindices.

```java
public interface IStyleSheetList : IEnumerable<ICSSStyleSheet>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/istylesheetlist/item/) De item(index)-methode moet het index‑de [`CSS style sheet`](../icssstylesheet/) in de collectie retourneren. Als er geen index‑de object in de collectie bestaat, moet de methode null retourneren. |
| [getLength](../../com.aspose.html.dom.css/istylesheetlist/length/) Het length‑attribuut moet het aantal CSS‑stijlbladen dat door de collectie wordt vertegenwoordigd retourneren. Het bereik van geldige child‑stylesheet‑indices is 0 tot en met length‑1. |

## Opmerkingen

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referentie

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # stylesheetlist](https://drafts.csswg.org/cssom/#stylesheetlist) – The CSSOM definition.

### Zie ook

* interface [ICSSStyleSheet](../icssstylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
