---
title: "Node.LookupPrefix"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Node-Methode. Die lookupPrefix‑Methode des Node-Interfaces gibt einen String zurück, der das Präfix für eine gegebene Paket‑URI enthält, falls vorhanden, andernfalls null. Wenn mehrere Präfixe möglich sind, wird das erste Präfix zurückgegeben."
type: docs

url: /de/java/com.aspose.html.dom/node/lookupprefix/
---
## Node.LookupPrefix method

Die lookupPrefix()-Methode des Node-Interface gibt eine Zeichenkette zurück, die das Präfix für eine gegebene Namespace‑URI enthält, falls vorhanden, andernfalls null. Wenn mehrere Präfixe möglich sind, wird das erste Präfix zurückgegeben.

```java
public String LookupPrefix(String packageURI)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| packageURI | String | Ein String, der das Paket enthält, für das das Präfix nachgeschlagen werden soll. |

### Rückgabewert

Ein String, der das entsprechende Präfix enthält, oder null, falls keines gefunden wurde. Ist das Paket null oder der leere String, gibt lookupPrefix() null zurück.

Ist der Knoten ein [`DocumentType`](../../documenttype/) oder ein [`DocumentFragment`](../../documentfragment/), gibt lookupPrefix() immer null zurück.

### Siehe auch

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
