---
title: "IWindow.Btoa"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IWindow-methode. Neemt de invoergegevens in de vorm van een Unicode-string die alleen tekens bevat in het bereik U0000 tot U00FF, elk een binair byte met waarden 0x00 tot 0xFF representerend, en zet deze om naar zijn base64-representatie die wordt geretourneerd."
type: docs

url: /nl/java/com.aspose.html.window/iwindow/btoa/
---
## IWindow.Btoa method

Neemt de invoergegevens in de vorm van een Unicode-String die alleen tekens bevat in het bereik U+0000 tot U+00FF, elk een binair byte met waarden 0x00 tot 0xFF respectievelijk, en zet deze om naar de base64-representatie, die wordt geretourneerd.

```java
public String Btoa(String data)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gegevens | String | De Unicode-string die alleen tekens bevat in het bereik U+0000 tot U+00FF. |

### Retourwaarde

De base64-string.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Gooit een "InvalidCharacterError" DOMException-exception als de invoer-string tekens buiten het bereik bevat. |

### Zie ook

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
