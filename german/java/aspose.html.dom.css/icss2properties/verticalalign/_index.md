---
title: "ICSS2Properties.VerticalAlign"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSS2Properties-Eigenschaft. Diese Eigenschaft beeinflusst die vertikale Positionierung innerhalb einer Zeilenbox der von einem Inline-Element erzeugten Boxen. Die folgenden Werte haben nur in Bezug auf ein übergeordnetes Inline-Element oder ein übergeordnetes Block-Element Bedeutung, wenn dieses Element anonyme Inline-Boxen erzeugt; sie haben keine Wirkung, wenn ein solcher übergeordneter Knoten nicht existiert."
type: docs

url: /de/java/com.aspose.html.dom.css/icss2properties/verticalalign/
---
## ICSS2Properties.VerticalAlign property

Diese Eigenschaft beeinflusst die vertikale Positionierung innerhalb einer Zeilenbox der von einem Inline-Element erzeugten Boxen. Die folgenden Werte haben nur in Bezug auf ein übergeordnetes Inline-Element oder ein übergeordnetes Block-Element Bedeutung, wenn dieses Element [anonyme Inline-Boxen](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#anonymous) erzeugt; sie haben keine Wirkung, wenn ein solcher übergeordneter Knoten nicht existiert.

Hinweis. Die Werte dieser Eigenschaft haben im Kontext von Tabellen leicht unterschiedliche Bedeutungen. Bitte lesen Sie den Abschnitt zu [Tabellenhöhenalgorithmen](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#height-layout) für Details. baseline – Ausrichtung der Grundlinie der Box an der Grundlinie der übergeordneten Box. Hat die Box keine Grundlinie, wird ihr unterer Rand an der Grundlinie des übergeordneten Elements ausgerichtet. middle – Ausrichtung des vertikalen Mittelpunkts der Box an der Grundlinie der übergeordneten Box plus die Hälfte der x-Höhe des übergeordneten Elements. sub – Senkt die Grundlinie der Box in die korrekte Position für Tiefstellungen des übergeordneten Elements. (Dieser Wert hat keinen Einfluss auf die Schriftgröße des Textes des Elements.) super – Hebt die Grundlinie der Box in die korrekte Position für Hochstellungen des übergeordneten Elements. (Dieser Wert hat keinen Einfluss auf die Schriftgröße des Textes des Elements.) text-top – Ausrichtung des oberen Randes der Box an der Oberkante der Schrift des übergeordneten Elements. text-bottom – Ausrichtung des unteren Randes der Box an der Unterkante der Schrift des übergeordneten Elements. '[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' – Erhöht (positiver Wert) oder senkt (negativer Wert) die Box um diesen Abstand (ein Prozentsatz des ['line-height'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-line-height)-Wertes). Der Wert '0%' bedeutet dasselbe wie 'baseline'. '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' – Erhöht (positiver Wert) oder senkt (negativer Wert) die Box um diesen Abstand. Der Wert '0cm' bedeutet dasselbe wie 'baseline'. top – Ausrichtung des oberen Randes der Box an der Oberkante der Zeilenbox. bottom – Ausrichtung des unteren Randes der Box an der Unterkante der Zeilenbox.

```java
public String VerticalAlign { get; set; }
```

### Rückgabewert

vertical-align-Eigenschaft

### Siehe auch

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
