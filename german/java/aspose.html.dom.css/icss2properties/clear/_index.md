---
title: "ICSS2Properties.Clear"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSS2Properties-Eigenschaft. Diese Eigenschaft gibt an, welche Seiten der Boxen eines Elements nicht an eine zuvor schwebende Box angrenzen dürfen. Es kann sein, dass das Element selbst schwebende Nachfahren hat; die clear‑Eigenschaft hat darauf keinen Einfluss."
type: docs

url: /de/java/com.aspose.html.dom.css/icss2properties/clear/
---
## ICSS2Properties.Clear property

Diese Eigenschaft gibt an, welche Seiten der Box(en) eines Elements nicht an eine zuvor schwebende Box angrenzen dürfen. (Es kann sein, dass das Element selbst schwebende Nachfahren hat; die 'clear'-Eigenschaft hat darauf keinen Einfluss.)

Diese Eigenschaft darf nur für Block-Elemente (einschließlich Floats) angegeben werden. Für kompakte und run-in-Boxen gilt diese Eigenschaft für die abschließende Block-Box, zu der die kompakte oder run-in-Box gehört.

Werte haben die folgende Bedeutung, wenn sie auf nicht schwebende Block-Boxen angewendet werden:

left - Der obere Rand der erzeugten Box wird so weit vergrößert, dass die obere Randkante unter der unteren Außenkante aller links schwebenden Boxen liegt, die aus früheren Elementen im Quell-Dokument resultierten. right - Der obere Rand der erzeugten Box wird so weit vergrößert, dass die obere Randkante unter der unteren Außenkante aller rechts schwebenden Boxen liegt, die aus früheren Elementen im Quell-Dokument resultierten. both - Die erzeugte Box wird unter alle schwebenden Boxen früherer Elemente im Quell-Dokument verschoben. none - Keine Einschränkung für die Position der Box in Bezug auf Floats.

```java
public String Clear { get; set; }
```

### Rückgabewert

clear-Eigenschaft

### Siehe auch

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
