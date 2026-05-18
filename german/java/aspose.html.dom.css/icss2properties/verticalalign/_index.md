---
title: "ICSS2Properties.VerticalAlign"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSS2Properties-Eigenschaft. Diese Eigenschaft beeinflusst die vertikale Positionierung innerhalb einer Zeilenbox der von einem Inline-Level-Element erzeugten Boxen. Die folgenden Werte haben nur in Bezug auf ein übergeordnetes Inline-Level-Element oder ein übergeordnetes Block-Level-Element Bedeutung, wenn dieses Element anonyme Inline-Boxen erzeugt; sie haben keine Wirkung, wenn ein solches übergeordnetes Element nicht existiert."
type: docs

url: /de/java/com.aspose.html.dom.css/icss2properties/verticalalign/
---
## ICSS2Properties.VerticalAlign property

Diese Eigenschaft beeinflusst die vertikale Positionierung innerhalb einer Zeilenbox der von einem Inline-Level-Element erzeugten Boxen. Die folgenden Werte haben nur in Bezug auf ein übergeordnetes Inline-Level-Element oder ein übergeordnetes Block-Level-Element Bedeutung, wenn dieses Element [anonyme Inline-Boxen](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#anonymous) erzeugt; sie haben keine Wirkung, wenn ein solches übergeordnetes Element nicht existiert.

Hinweis. Die Werte dieser Eigenschaft haben im Kontext von Tabellen leicht unterschiedliche Bedeutungen. Bitte lesen Sie den Abschnitt zu den [Tabellenhöhen-Algorithmen](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#height-layout) für Details. baseline – Ausrichtung der Grundlinie der Box an der Grundlinie der übergeordneten Box. Wenn die Box keine Grundlinie hat, wird die Unterseite der Box an der Grundlinie des Elternteils ausgerichtet. middle – Ausrichtung des vertikalen Mittelpunkts der Box an der Grundlinie der übergeordneten Box plus die halbe x-Höhe des Elternteils. sub – Senkt die Grundlinie der Box auf die korrekte Position für Unterscripte des Elternteils. (Dieser Wert hat keinen Einfluss auf die Schriftgröße des Textelements.) super – Hebt die Grundlinie der Box auf die korrekte Position für Ober­scripte des Elternteils. (Dieser Wert hat keinen Einfluss auf die Schriftgröße des Textelements.) text-top – Ausrichtung der Oberseite der Box an der Oberseite der Schrift des übergeordneten Elements. text-bottom – Ausrichtung der Unterseite der Box an der Unterseite der Schrift des übergeordneten Elements. ['percentage'](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage) – Erhöht (positiver Wert) oder senkt (negativer Wert) die Box um diesen Abstand (ein Prozentsatz des ['line-height'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-line-height)-Wertes). Der Wert '0%' bedeutet dasselbe wie 'baseline'. ['length'](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length) – Erhöht (positiver Wert) oder senkt (negativer Wert) die Box um diesen Abstand. Der Wert '0cm' bedeutet dasselbe wie 'baseline'. top – Ausrichtung der Oberseite der Box an der Oberseite der Zeilenbox. bottom – Ausrichtung der Unterseite der Box an der Unterseite der Zeilenbox.

```java
public String VerticalAlign { get; set; }
```

### Rückgabewert

vertical-align-Eigenschaft

### Siehe auch

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
