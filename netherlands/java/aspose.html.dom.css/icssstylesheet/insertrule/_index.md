---
title: "ICSSStyleSheet.InsertRule"
second_title: "Aspose.HTML voor Java API-referentie"
description: "ICSSStyleSheet-methode. De CSSStyleSheet.insertRule-methode voegt een nieuwe CSS-regel toe aan het huidige stylesheet met enkele beperkingen"
type: docs

url: /nl/java/com.aspose.html.dom.css/icssstylesheet/insertrule/
---
## ICSSStyleSheet.InsertRule method

De CSSStyleSheet.insertRule()‑methode voegt een nieuwe CSS‑regel toe aan het huidige stylesheet, met enkele beperkingen.

Opmerking: hoewel insertRule() uitsluitend een methode is van [`CSSStyleSheet`](../), voegt het de regel eigenlijk toe aan CSSStyleSheet.cssRules — de interne [`CSSRuleList`](../../icssrulelist/).

```java
public long InsertRule(String rule, int index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| regel | String | Een String die de in te voegen regel bevat. Wat de ingevoegde regel moet bevatten, hangt af van het type: |
| index | Int32 | Een positief geheel getal kleiner dan of gelijk aan stylesheet.cssRules.length, dat de positie van de nieuw ingevoegde regel in CSSStyleSheet.cssRules aangeeft. Standaard is 0. |

### Retourwaarde

De index van de nieuw ingevoegde regel binnen de regel‑lijst van het stylesheet.

## Opmerkingen

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referentie

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-cssstylesheet-insertrule](https://drafts.csswg.org/cssom/#dom-cssstylesheet-insertrule) – The CSSOM definition.

### Zie ook

* interface [ICSSStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
