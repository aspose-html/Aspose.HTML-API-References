---
title: "Document.CreateElement"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Document-Methode. In einem HTML-Dokument erstellt die Methode document.createElement das HTML-Element, das durch tagName angegeben ist, oder ein HTMLUnknownElement, wenn tagName nicht erkannt wird."
type: docs

url: /de/java/com.aspose.html.dom/document/createelement/
---
## Document.CreateElement method

In einem HTML-Dokument erstellt die Methode document.createElement() das HTML-Element, das durch tagName angegeben ist, oder ein [`HTMLUnknownElement`](../../../com.aspose.html/htmlunknownelement/), wenn tagName nicht erkannt wird.

```java
public Element CreateElement(String localName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | String | Ein String, der den Typ des zu erstellenden Elements angibt. Der nodeName des erstellten Elements wird mit dem Wert von tagName initialisiert. Verwenden Sie keine qualifizierten Namen (wie "html:a") mit dieser Methode. Wird die Methode in einem HTML-Dokument aufgerufen, konvertiert createElement() tagName in Kleinbuchstaben, bevor das Element erstellt wird. |

### Rückgabewert

Das neue [`Element`](../../element/).

## Beispiele

```java
var element = document.CreateElement(tagName);
```

### Siehe auch

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
