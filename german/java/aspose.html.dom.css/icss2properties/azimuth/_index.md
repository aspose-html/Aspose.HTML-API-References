---
title: "ICSS2Properties.Azimuth"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSS2Properties Eigenschaft. Räumlicher Klang ist eine wichtige stilistische Eigenschaft für die akustische Darstellung. Er bietet eine natürliche Möglichkeit, mehrere Stimmen zu unterscheiden, da Menschen im wirklichen Leben selten alle am selben Ort in einem Raum stehen."
type: docs

url: /de/java/com.aspose.html.dom.css/icss2properties/azimuth/
---
## ICSS2Properties.Azimuth property

Räumlicher Klang ist eine wichtige stilistische Eigenschaft für die akustische Darstellung. Er bietet eine natürliche Möglichkeit, mehrere Stimmen zu unterscheiden, wie im wirklichen Leben (Menschen selten alle am selben Ort in einem Raum stehen).

```java
public String Azimuth { get; set; }
```

### Rückgabewert

Die Azimut-Eigenschaft

### Property Value

Die Werte haben die folgende Bedeutung:

Winkel - Die Position wird in Form eines Winkels im Bereich von '-360deg' bis '360deg' beschrieben. Der Wert '0deg' bedeutet direkt vorne in der Mitte der Klangbühne. '90deg' ist nach rechts, '180deg' nach hinten und '270deg' (oder, äquivalent und bequemer, '-90deg') nach links.

linke Seite - Gleich wie '270deg'. Mit 'behind', '270deg'.

weit links - Gleich wie '300deg'. Mit 'behind', '240deg'.

links - Gleich wie '320deg'. Mit 'behind', '220deg'.

Mitte-links - Gleich wie '340deg'. Mit 'behind', '200deg'.

Mitte - Gleich wie '0deg'. Mit 'behind', '180deg'.

Mitte-rechts - Gleich wie '20deg'. Mit 'behind', '160deg'.

rechts - Gleich wie '40deg'. Mit 'behind', '140deg'.

weit rechts - Gleich wie '60deg'. Mit 'behind', '120deg'.

rechte Seite - Gleich wie '90deg'. Mit 'behind', '90deg'.

nach links - Verschiebt den Klang nach links, relativ zum aktuellen Winkel. Genauer gesagt, subtrahiert es 20 Grad. Die Arithmetik wird modulo 360 Grad durchgeführt. Hinweis, dass 'nach links' genauer als "gegen den Uhrzeigersinn gedreht" beschrieben wird, da es immer 20 Grad subtrahiert, selbst wenn der vererbte Azimut bereits hinter dem Hörer liegt (in diesem Fall erscheint der Klang tatsächlich nach rechts zu bewegen).

nach rechts - Verschiebt den Klang nach rechts, relativ zum aktuellen Winkel. Genauer gesagt, addiert es 20 Grad. Siehe 'nach links' für die Arithmetik.

### Siehe auch

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
