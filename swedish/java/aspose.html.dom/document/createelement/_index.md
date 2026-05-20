---
title: "Document.CreateElement"
second_title: "Aspose.HTML för Java API-referens"
description: "Document‑metod. I ett HTML‑dokument skapar document.createElement‑metoden HTML‑elementet som anges av tagName eller ett HTMLUnknownElement om tagName inte känns igen."
type: docs

url: /sv/java/com.aspose.html.dom/document/createelement/
---
## Document.CreateElement method

I ett HTML‑dokument skapar document.createElement()‑metoden HTML‑elementet som anges av tagName, eller ett [`HTMLUnknownElement`](../../../com.aspose.html/htmlunknownelement/) om tagName inte känns igen.

```java
public Element CreateElement(String localName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | String | En sträng som anger typen av element som ska skapas. nodeName för det skapade elementet initieras med värdet av tagName. Använd inte kvalificerade namn (t.ex. "html:a") med denna metod. När den anropas på ett HTML‑dokument konverterar createElement() tagName till gemener innan elementet skapas. |

### Returvärde

Det nya [`Element`](../../element/).

## Exempel

```java
var element = document.CreateElement(tagName);
```

### Se även

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
