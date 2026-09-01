---
title: "RGBColor Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.css.RGBColor Klasse. Das RGBColor-Interface wird verwendet, um jeden RGB-Farbwert darzustellen. Dieses Interface spiegelt die Werte in der zugrunde liegenden Style-Eigenschaft wider. Daher ändern Änderungen an den CSSPrimitiveValue-Objekten die Style-Eigenschaft."
type: docs

url: /de/java/com.aspose.html.dom.css/rgbcolor/
---
## RGBColor class

Das RGBColor‑Interface wird verwendet, um jeden RGB‑Farbwert darzustellen. Dieses Interface spiegelt die Werte in der zugrunde liegenden Style‑Eigenschaft wider. Daher ändern Änderungen an den CSSPrimitiveValue‑Objekten die Style‑Eigenschaft.

Eine angegebene RGB-Farbe wird nicht abgeschnitten (auch wenn die Zahl außerhalb des Bereichs 0‑255 oder 0 %‑100 % liegt). Eine berechnete RGB-Farbe wird je nach Gerät abgeschnitten.

Selbst wenn ein Stylesheet für einen Farbwert nur einen Integer enthalten kann, wird dieser Integer intern als Float gespeichert und kann als Float im angegebenen oder berechneten Stil verwendet werden.

Ein prozentualer Farbwert kann jederzeit in eine Zahl umgewandelt werden und umgekehrt.

```java
public class RGBColor : DOMObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getAlpha](../../com.aspose.html.dom.css/rgbcolor/alpha/) Gibt den Alpha-Komponentenwert dieser Color-Struktur zurück. |
| [getBlue](../../com.aspose.html.dom.css/rgbcolor/blue/) Gibt den Blau-Komponentenwert dieser Color-Struktur zurück. |
| [getGreen](../../com.aspose.html.dom.css/rgbcolor/green/) Gibt den Grün-Komponentenwert dieser Color-Struktur zurück. |
| [getRed](../../com.aspose.html.dom.css/rgbcolor/red/) Gibt den Rot-Komponentenwert dieser Color-Struktur zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript-Objekt abzurufen. |
| [toNative](../../com.aspose.html.dom.css/rgbcolor/tonative/)() | Konvertiert in das native Farbobjekt. |

## Hinweise

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Referenz

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### Siehe auch

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
