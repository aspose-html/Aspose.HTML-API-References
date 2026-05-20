---
title: "RGBColor klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.css.RGBColor-klass. RGBColor-gränssnittet används för att representera vilket RGB-färgvärde som helst. Detta gränssnitt speglar värdena i den underliggande stil‑egenskapen. Därför modifierar ändringar som görs på CSSPrimitiveValue‑objekten stil‑egenskapen."
type: docs

url: /sv/java/com.aspose.html.dom.css/rgbcolor/
---
## RGBColor class

RGBColor‑gränssnittet används för att representera vilket som helst RGB‑färgvärde. Detta gränssnitt återspeglar värdena i den underliggande stil‑egenskapen. Därför modifierar ändringar som görs på CSSPrimitiveValue‑objekten stil‑egenskapen.

En specificerad RGB‑färg klipps inte (även om talet ligger utanför intervallet 0‑255 eller 0 %‑100 %). En beräknad RGB‑färg klipps beroende på enheten.

Även om ett formatark bara kan innehålla ett heltal för ett färgvärde, lagras detta heltal internt som ett flyttal, och detta kan användas som ett flyttal i den specificerade eller den beräknade stilen.

Ett färgprocentvärde kan alltid konverteras till ett tal och vice versa.

```java
public class RGBColor : DOMObject
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getAlpha](../../com.aspose.html.dom.css/rgbcolor/alpha/) Hämtar alfakomponentens värde för denna Color‑struktur. |
| [getBlue](../../com.aspose.html.dom.css/rgbcolor/blue/) Hämtar den blå komponentens värde för denna Color‑struktur. |
| [getGreen](../../com.aspose.html.dom.css/rgbcolor/green/) Hämtar den gröna komponentens värde för denna Color‑struktur. |
| [getRed](../../com.aspose.html.dom.css/rgbcolor/red/) Hämtar den röda komponentens värde för denna Color‑struktur. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [toNative](../../com.aspose.html.dom.css/rgbcolor/tonative/)() | Konverterar till det inbyggda färgobjektet. |

## Anmärkningar

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referens

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### Se även

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
