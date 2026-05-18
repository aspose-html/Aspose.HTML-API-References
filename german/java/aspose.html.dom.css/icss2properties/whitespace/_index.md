---
title: "ICSS2Properties.WhiteSpace"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ICSS2Properties-Eigenschaft. Diese Eigenschaft legt fest, wie Leerzeichen innerhalb des Elements behandelt werden. Werte haben die folgende Bedeutung"
type: docs

url: /de/java/com.aspose.html.dom.css/icss2properties/whitespace/
---
## ICSS2Properties.WhiteSpace property

Diese Eigenschaft legt fest, wie [whitespace](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#whitespace) innerhalb des Elements behandelt wird. Werte haben die folgende Bedeutung:

normal - Dieser Wert weist Benutzeragenten an, Leerzeichenfolgen zu kollabieren und Zeilen nach Bedarf zu umbrechen, um Zeilenboxen zu füllen. Zusätzliche Zeilenumbrüche können durch Vorkommen von "\A" im generierten Inhalt erzeugt werden (z. B. für das BR-Element in HTML).pre - Dieser Wert verhindert, dass Benutzeragenten Leerzeichenfolgen kollabieren. Zeilen werden nur bei Zeilenumbrüchen im Quelltext oder bei Vorkommen von "\A" im generierten Inhalt umgebrochen.nowrap - Dieser Wert kollabiert Leerzeichen wie bei 'normal', unterdrückt jedoch Zeilenumbrüche im Text, außer denen, die durch "\A" im generierten Inhalt erzeugt werden (z. B. für das BR-Element in HTML).

```java
public String WhiteSpace { get; set; }
```

### Rückgabewert

white-space-Eigenschaft

### Siehe auch

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
