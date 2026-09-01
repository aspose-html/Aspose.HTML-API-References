---
title: "Event.PreventDefault"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Ereignismethode. Wenn ein Ereignis abbrechbar ist, wird die PreventDefault‑Methode verwendet, um anzuzeigen, dass das Ereignis abgebrochen werden soll, was bedeutet, dass jede standardmäßige Aktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt wird, nicht erfolgt."
type: docs

url: /de/java/com.aspose.html.dom.events/event/preventdefault/
---
## Event.PreventDefault method

Wenn ein Ereignis abbrechbar ist, wird die `PreventDefault`‑Methode verwendet, um anzuzeigen, dass das Ereignis abgebrochen werden soll, was bedeutet, dass jede standardmäßige Aktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt wird, nicht erfolgt.

```java
public void PreventDefault()
```

## Hinweise

Wenn während irgendeiner Phase des Ereignisflusses die `PreventDefault`‑Methode aufgerufen wird, wird das Ereignis abgebrochen. Jede mit dem Ereignis verbundene Standardaktion wird nicht ausgeführt. Der Aufruf dieser Methode für ein nicht abbrechbares Ereignis hat keine Wirkung. Sobald `PreventDefault` aufgerufen wurde, bleibt es für den Rest der Ereignispropagation wirksam. Diese Methode kann in jeder Phase des Ereignisflusses verwendet werden.

### Siehe auch

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
