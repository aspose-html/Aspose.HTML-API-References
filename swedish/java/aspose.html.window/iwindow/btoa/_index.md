---
title: "IWindow.Btoa"
second_title: "Aspose.HTML för Java API-referens"
description: "IWindow‑metod. Tar indata i form av en Unicode‑sträng som bara innehåller tecken i intervallet U0000 till U00FF, där varje tecken representerar en binär byte med värdena 0x00 till 0xFF, och konverterar den till dess base64‑representation som den returnerar."
type: docs

url: /sv/java/com.aspose.html.window/iwindow/btoa/
---
## IWindow.Btoa method

Tar emot indata i form av en Unicode-sträng som endast innehåller tecken i intervallet U+0000 till U+00FF, där varje tecken representerar en binär byte med värden 0x00 till 0xFF respektive, och konverterar den till dess base64-representation, som den returnerar.

```java
public String Btoa(String data)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | String | Unicode‑strängen som bara innehåller tecken i intervallet U+0000 till U+00FF. |

### Returvärde

Base64‑strängen.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kastar ett "InvalidCharacterError" DOMException‑undantag om indata‑strängen innehåller tecken utanför intervallet. |

### Se även

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
