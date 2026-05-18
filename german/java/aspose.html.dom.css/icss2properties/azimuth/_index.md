---
title: "ICSS2Properties.Azimuth"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSS2Properties Eigenschaft. Räumlicher Klang ist eine wichtige stilistische Eigenschaft für die akustische Darstellung. Er bietet eine natürliche Möglichkeit, mehrere Stimmen zu unterscheiden, da Menschen im wirklichen Leben selten alle am selben Ort im Raum stehen."
type: docs

url: /de/java/com.aspose.html.dom.css/icss2properties/azimuth/
---
## ICSS2Properties.Azimuth property

Räumlicher Klang ist eine wichtige stilistische Eigenschaft für die akustische Darstellung. Er bietet eine natürliche Möglichkeit, mehrere Stimmen zu unterscheiden, wie im wirklichen Leben (Menschen stehen selten alle am selben Ort im Raum).

```java
public String Azimuth { get; set; }
```

### Rückgabewert

Die azimuth-Eigenschaft

### Property Value

Die Werte haben die folgende Bedeutung:

angle - Position wird in Form eines Winkels im Bereich von '-360deg' bis '360deg' beschrieben. Der Wert '0deg' bedeutet direkt vorne in der Mitte der Klangbühne. '90deg' ist nach rechts, '180deg' nach hinten und '270deg' (oder äquivalent und praktischer '-90deg') nach links.

left-side - Gleich wie '270deg'. Mit 'behind', '270deg'.

far-left - Gleich wie '300deg'. Mit 'behind', '240deg'.

left - Gleich wie '320deg'. Mit 'behind', '220deg'.

center-left - Gleich wie '340deg'. Mit 'behind', '200deg'.

center - Gleich wie '0deg'. Mit 'behind', '180deg'.

center-right - Gleich wie '20deg'. Mit 'behind', '160deg'.

right - Gleich wie '40deg'. Mit 'behind', '140deg'.

far-right - Gleich wie '60deg'. Mit 'behind', '120deg'.

right-side - Gleich wie '90deg'. Mit 'behind', '90deg'.

leftwards - Bewegt den Klang nach links, relativ zum aktuellen Winkel. Genauer gesagt, subtrahiert es 20 Grad. Die Arithmetik wird modulo 360 Grad durchgeführt. Hinweis: 'leftwards' wird genauer als \"gegen den Uhrzeigersinn gedreht\" beschrieben, da es stets 20 Grad subtrahiert, selbst wenn der vererbte Azimut bereits hinter dem Hörer liegt (in welchem Fall der Klang tatsächlich nach rechts zu bewegen scheint).

rightwards - Bewegt den Klang nach rechts, relativ zum aktuellen Winkel. Genauer gesagt, addiert es 20 Grad. Siehe 'leftwards' für die Arithmetik.

### Siehe auch

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
