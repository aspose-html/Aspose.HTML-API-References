---
title: "ICSS2Properties.TextShadow"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSS2Properties-Eigenschaft. Diese Eigenschaft akzeptiert eine kommagetrennte Liste von Schatteneffekten, die auf den Text des Elements angewendet werden. Die Schatteneffekte werden in der angegebenen Reihenfolge angewendet und können sich dabei überlagern, jedoch werden sie niemals den Text selbst überlagern. Schatteneffekte verändern nicht die Größe eines Elements, können jedoch über dessen Grenzen hinausreichen. Die Stapelstufe der Schatteneffekte ist dieselbe wie die des Elements selbst."
type: docs

url: /de/java/com.aspose.html.dom.css/icss2properties/textshadow/
---
## ICSS2Properties.TextShadow property

Diese Eigenschaft akzeptiert eine kommagetrennte Liste von Schatteneffekten, die auf den Text des Elements angewendet werden. Die Schatteneffekte werden in der angegebenen Reihenfolge angewendet und können sich dabei überlagern, jedoch werden sie niemals den Text selbst überlagern. Schatteneffekte verändern nicht die Größe eines Elements, können jedoch über dessen Grenzen hinausreichen. Die [stack level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#stack-level) der Schatteneffekte ist dieselbe wie die des Elements selbst.

Jeder Schatteneffekt muss einen Schattenversatz angeben und kann optional einen Unschärferadius sowie eine Schattenfarbe angeben.

Ein Schattenversatz wird mit zwei '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' Werten angegeben, die den Abstand vom Text angeben. Der erste Längenwert gibt den horizontalen Abstand rechts vom Text an. Ein negativer horizontaler Längenwert platziert den Schatten links vom Text. Der zweite Längenwert gibt den vertikalen Abstand unterhalb des Textes an. Ein negativer vertikaler Längenwert platziert den Schatten über dem Text.

Ein Unschärferadius kann optional nach dem Schattenversatz angegeben werden. Der Unschärferadius ist ein Längenwert, der die Grenzen des Unschärfeeffekts angibt. Der genaue Algorithmus zur Berechnung des Unschärfeeffekts ist nicht spezifiziert.

Ein Farbwert kann optional vor oder nach den Längenwerten des Schatteneffekts angegeben werden. Der Farbwert wird als Grundlage für den Schatteneffekt verwendet. Wenn keine Farbe angegeben ist, wird stattdessen der Wert der ['color'](https://www.w3.org/TR/1998/REC-CSS2-19980512/colors.html#propdef-color) Eigenschaft verwendet.

```java
public String TextShadow { get; set; }
```

### Rückgabewert

text-shadow-Eigenschaft

### Siehe auch

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
