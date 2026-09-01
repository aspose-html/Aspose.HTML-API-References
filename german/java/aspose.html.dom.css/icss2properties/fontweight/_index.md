---
title: "ICSS2Properties.FontWeight"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSS2Properties-Eigenschaft. Die font-weight-Eigenschaft gibt das Gewicht der Schrift an. Werte haben die folgende Bedeutung"
type: docs

url: /de/java/com.aspose.html.dom.css/icss2properties/fontweight/
---
## ICSS2Properties.FontWeight property

Die 'font-weight'-Eigenschaft gibt das Gewicht der Schrift an. Werte haben die folgende Bedeutung:

100 bis 900 – Diese Werte bilden eine geordnete Sequenz, wobei jede Zahl ein Gewicht angibt, das mindestens so dunkel ist wie das vorherige. normal – Entspricht '400'. bold – Entspricht '700'. bolder – Gibt das nächste Gewicht an, das einer Schrift zugewiesen wird, die dunkler ist als die vererbte. Gibt es kein solches Gewicht, führt dies einfach zum nächsten dunkleren numerischen Wert (und die Schrift bleibt unverändert), es sei denn, der vererbte Wert war '900', dann bleibt das resultierende Gewicht ebenfalls '900'. lighter – Gibt das nächste Gewicht an, das einer Schrift zugewiesen wird, die leichter ist als die vererbte. Gibt es kein solches Gewicht, führt dies einfach zum nächsten leichteren numerischen Wert (und die Schrift bleibt unverändert), es sei denn, der vererbte Wert war '100', dann bleibt das resultierende Gewicht ebenfalls '100'.

```java
public String FontWeight { get; set; }
```

### Rückgabewert

font-weight-Eigenschaft

### Siehe auch

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
