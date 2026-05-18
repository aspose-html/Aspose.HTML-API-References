---
title: "IWindow.Atob"
second_title: "Aspose.HTML für Java API-Referenz"
description: "IWindow-Methode. Nimmt die Eingabedaten in Form eines Unicode-Strings entgegen, der base64-kodierte Binärdaten enthält, dekodiert sie und gibt einen String zurück, der aus Zeichen im Bereich U0000 bis U00FF besteht, wobei jedes Zeichen ein Binärbyte mit den Werten 0x00 bis 0xFF darstellt, das den Binärdaten entspricht."
type: docs

url: /de/java/com.aspose.html.window/iwindow/atob/
---
## IWindow.Atob method

Nimmt die Eingabedaten in Form eines Unicode‑Strings, der base64‑kodierte Binärdaten enthält, dekodiert sie und gibt einen String zurück, der aus Zeichen im Bereich U+0000 bis U+00FF besteht, wobei jedes Zeichen ein Binärbyte mit den Werten 0x00 bis 0xFF repräsentiert, entsprechend den binären Daten.

```java
public String Atob(String data)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | String | Der Unicode-String, der base64-kodierte Binärdaten enthält. |

### Rückgabewert

Der String, der aus Zeichen im Bereich U+0000 bis U+00FF besteht.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Wirft eine "InvalidCharacterError" DOMException, wenn der Eingabe-String keine gültigen Base64-Daten enthält. |

### Siehe auch

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
