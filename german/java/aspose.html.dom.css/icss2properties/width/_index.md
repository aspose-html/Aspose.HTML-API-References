---
title: "ICSS2Properties.Width"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSS2Properties Eigenschaft. Diese Eigenschaft gibt die Inhaltsbreite von Boxen an, die durch Block‑Level‑ und ersetzte Elemente erzeugt werden."
type: docs

url: /de/java/com.aspose.html.dom.css/icss2properties/width/
---
## ICSS2Properties.Width property

Diese Eigenschaft gibt die [Inhaltsbreite](https://www.w3.org/TR/1998/REC-CSS2-19980512/box.html#content-width) von Boxen an, die durch Block‑Level‑ und [ersetzte](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#replaced-element) Elemente erzeugt werden.

Diese Eigenschaft gilt nicht für nicht ersetzte [inline-level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#inline-level) Elemente. Die Breite der Boxen eines nicht ersetzten Inline-Elements entspricht dem gerenderten Inhalt darin (vor jeglichem relativen Versatz der Kinder). Denken Sie daran, dass Inline-Boxen in [line boxes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#line-box) fließen. Die Breite von Zeilenboxen wird durch ihren [containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block) bestimmt, kann jedoch durch das Vorhandensein von [floats](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#floats) verkürzt werden.

Die Breite der Box eines ersetzten Elements ist [intrinsic](https://www.w3.org/TR/1998/REC-CSS2-19980512/conform.html#intrinsic) und kann vom User-Agent skaliert werden, wenn der Wert dieser Eigenschaft von 'auto' abweicht.

Die Werte haben die folgende Bedeutung:

'[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - Gibt eine feste Breite an.'[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Gibt eine prozentuale Breite an. Der Prozentsatz wird bezogen auf die Breite des erzeugten Box-[containing block](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#containing-block) berechnet.auto - Die Breite hängt von den Werten anderer Eigenschaften ab. Siehe die nachfolgenden Abschnitte.Hinweis: Negative Werte für ['width'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-width) sind illegal.

```java
public String Width { get; set; }
```

### Rückgabewert

width-Eigenschaft

### Siehe auch

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
