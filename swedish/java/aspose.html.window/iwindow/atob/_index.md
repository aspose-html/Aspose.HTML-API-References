---
title: "IWindow.Atob"
second_title: "Aspose.HTML för Java API-referens"
description: "IWindow‑metod. Tar indata i form av en Unicode String som innehåller base64‑kodad binär data, avkodar den och returnerar en String bestående av tecken i intervallet U0000 till U00FF, där varje tecken representerar en binär byte med värdena 0x00 till 0xFF som motsvarar den binära datan."
type: docs

url: /sv/java/com.aspose.html.window/iwindow/atob/
---
## IWindow.Atob method

Tar emot indata i form av en Unicode-sträng som innehåller base64-kodad binär data, avkodar den och returnerar en sträng bestående av tecken i intervallet U+0000 till U+00FF, där varje tecken representerar en binär byte med värden 0x00 till 0xFF respektive, motsvarande den binära datan.

```java
public String Atob(String data)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | String | Unicode String som innehåller base64‑kodad binär data |

### Returvärde

String som består av tecken i intervallet U+0000 till U+00FF

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kastar ett "InvalidCharacterError" DOMException‑undantag om indata‑strängen inte är giltig base64‑data. |

### Se även

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
