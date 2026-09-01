---
title: "RGBColor Class"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.css.RGBColor class. De RGBColor-interface wordt gebruikt om elke RGB-kleurwaarde te vertegenwoordigen. Deze interface weerspiegelt de waarden in de onderliggende stijl‑eigenschap. Daarom wijzigen aanpassingen aan de CSSPrimitiveValue‑objecten de stijl‑eigenschap."
type: docs

url: /nl/java/com.aspose.html.dom.css/rgbcolor/
---
## RGBColor class

De RGBColor-interface wordt gebruikt om elke RGB‑kleurwaarde weer te geven. Deze interface weerspiegelt de waarden in de onderliggende stijl‑eigenschap. Daarom wijzigen aanpassingen aan de CSSPrimitiveValue‑objecten de stijl‑eigenschap.

Een opgegeven RGB-kleur wordt niet bijgesneden (zelfs als het getal buiten het bereik 0‑255 of 0 %‑100 % valt). Een berekende RGB-kleur wordt bijgesneden afhankelijk van het apparaat.

Zelfs als een stylesheet alleen een geheel getal voor een kleurwaarde kan bevatten, wordt dit geheel getal intern opgeslagen als een float, en kan deze als float worden gebruikt in de opgegeven of de berekende stijl.

Een kleurpercentage‑waarde kan altijd worden omgezet naar een getal en omgekeerd.

```java
public class RGBColor : DOMObject
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getAlpha](../../com.aspose.html.dom.css/rgbcolor/alpha/) Haalt de alfa‑componentwaarde van deze Color‑structuur op. |
| [getBlue](../../com.aspose.html.dom.css/rgbcolor/blue/) Haalt de blauwe componentwaarde van deze Color‑structuur op. |
| [getGreen](../../com.aspose.html.dom.css/rgbcolor/green/) Haalt de groene componentwaarde van deze Color‑structuur op. |
| [getRed](../../com.aspose.html.dom.css/rgbcolor/red/) Haalt de rode componentwaarde van deze Color‑structuur op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [toNative](../../com.aspose.html.dom.css/rgbcolor/tonative/)() | Converteert naar het native kleurobject. |

## Opmerkingen

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referentie

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### Zie ook

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
