---
title: "IWindow.Btoa"
second_title: "Aspose.HTML für Java API-Referenz"
description: "IWindow-Methode. Nimmt die Eingabedaten in Form eines Unicode-Strings, der nur Zeichen im Bereich U0000 bis U00FF enthält, wobei jedes Zeichen ein Binärbyte mit den Werten 0x00 bis 0xFF darstellt, und konvertiert sie in ihre Base64-Darstellung, die zurückgegeben wird."
type: docs

url: /de/java/com.aspose.html.window/iwindow/btoa/
---
## IWindow.Btoa method

Nimmt die Eingabedaten in Form eines Unicode-Strings, der nur Zeichen im Bereich U+0000 bis U+00FF enthält, wobei jedes Zeichen ein Binärbyte mit den Werten 0x00 bis 0xFF darstellt, und konvertiert sie in ihre base64‑Darstellung, die zurückgegeben wird.

```java
public String Btoa(String data)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | String | Der Unicode-String, der nur Zeichen im Bereich U+0000 bis U+00FF enthält. |

### Rückgabewert

Der Base64-String.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Wirft eine "InvalidCharacterError" DOMException, wenn der Eingabe-String Zeichen außerhalb des zulässigen Bereichs enthält. |

### Siehe auch

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
