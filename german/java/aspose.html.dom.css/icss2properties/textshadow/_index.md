---
title: "ICSS2Properties.TextShadow"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSS2Properties-Eigenschaft. Diese Eigenschaft akzeptiert eine kommagetrennte Liste von Schatteneffekten, die auf den Text des Elements angewendet werden. Die Schatteneffekte werden in der angegebenen Reihenfolge angewendet und können sich dabei überlagern, jedoch werden sie niemals den Text selbst überlagern. Schatteneffekte ändern nicht die Größe einer Box, können jedoch über deren Grenzen hinausgehen. Die Stapelstufe der Schatteneffekte ist dieselbe wie die des Elements selbst."
type: docs

url: /de/java/com.aspose.html.dom.css/icss2properties/textshadow/
---
## ICSS2Properties.TextShadow property

Diese Eigenschaft akzeptiert eine kommagetrennte Liste von Schatteneffekten, die auf den Text des Elements angewendet werden. Die Schatteneffekte werden in der angegebenen Reihenfolge angewendet und können sich dabei überlagern, jedoch werden sie niemals den Text selbst überlagern. Schatteneffekte ändern nicht die Größe einer Box, können jedoch über deren Grenzen hinausgehen. Der [stack level](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#stack-level) der Schatteneffekte ist derselbe wie der des Elements selbst.

Jeder Schatteneffekt muss einen Schattenversatz angeben und kann optional einen Unschärmeradius sowie eine Schattenfarbe festlegen.

Ein Schattenversatz wird mit zwei '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)'-Werten angegeben, die den Abstand vom Text angeben. Der erste Längenwert gibt den horizontalen Abstand rechts vom Text an. Ein negativer horizontaler Längenwert positioniert den Schatten links vom Text. Der zweite Längenwert gibt den vertikalen Abstand unterhalb des Textes an. Ein negativer vertikaler Längenwert positioniert den Schatten über dem Text.

Ein Unschärmeradius kann optional nach dem Schattenversatz angegeben werden. Der Unschärmeradius ist ein Längenwert, der die Grenzen des Unschärfeeffekts angibt. Der genaue Algorithmus zur Berechnung des Unschärfeeffekts ist nicht spezifiziert.

Ein Farbwert kann optional vor oder nach den Längenwerten des Schatteneffekts angegeben werden. Der Farbwert wird als Grundlage für den Schatteneffekt verwendet. Wenn keine Farbe angegeben ist, wird stattdessen der Wert der ['color'](https://www.w3.org/TR/1998/REC-CSS2-19980512/colors.html#propdef-color)-Eigenschaft verwendet.

```java
public String TextShadow { get; set; }
```

### Rückgabewert

text-shadow-Eigenschaft

### Siehe auch

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
