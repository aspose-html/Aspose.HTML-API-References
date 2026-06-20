---
title: "ICSS2Properties.UnicodeBidi"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSS2Properties-Eigenschaft. Werte für diese Eigenschaft haben die folgenden Bedeutungen"
type: docs

url: /de/java/com.aspose.html.dom.css/icss2properties/unicodebidi/
---
## ICSS2Properties.UnicodeBidi property

Werte für diese Eigenschaft haben die folgenden Bedeutungen:

normal – Das Element eröffnet keinen zusätzlichen Einbettungsgrad in Bezug auf den bidirektionalen Algorithmus. Für Inline‑Elemente funktioniert die implizite Neuordnung über Elementgrenzen hinweg. embed – Wenn das Element Inline‑Level ist, öffnet dieser Wert einen zusätzlichen Einbettungsgrad in Bezug auf den bidirektionalen Algorithmus. Die Richtung dieses Einbettungsgrades wird durch die ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction)-Eigenschaft angegeben. Innerhalb des Elements wird die Neuordnung implizit durchgeführt. Dies entspricht dem Hinzufügen eines LRE (U+202A; für 'direction: ltr') oder RLE (U+202B; für 'direction: rtl') am Anfang des Elements und eines PDF (U+202C) am Ende des Elements. bidi-override – Wenn das Element Inline‑Level ist oder ein Block‑Element, das nur Inline‑Elemente enthält, erzeugt dies eine Überschreibung. Das bedeutet, dass innerhalb des Elements die Neuordnung strikt in der Reihenfolge gemäß der ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction)-Eigenschaft erfolgt; der implizite Teil des bidirektionalen Algorithmus wird ignoriert. Dies entspricht dem Hinzufügen eines LRO (U+202D; für 'direction: ltr') oder RLO (U+202E; für 'direction: rtl') am Anfang des Elements und eines PDF (U+202C) am Ende des Elements.

```java
public String UnicodeBidi { get; set; }
```

### Rückgabewert

unicode-bidi-Eigenschaft

### Siehe auch

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
