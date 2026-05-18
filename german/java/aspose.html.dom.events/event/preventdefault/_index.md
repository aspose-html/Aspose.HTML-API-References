---
title: "Event.PreventDefault"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Event-Methode. Wenn ein Ereignis abbrechbar ist, wird die PreventDefault‑Methode verwendet, um anzuzeigen, dass das Ereignis abgebrochen werden soll, was bedeutet, dass jede standardmäßige Aktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt wird, nicht stattfindet."
type: docs

url: /de/java/com.aspose.html.dom.events/event/preventdefault/
---
## Event.PreventDefault method

Wenn ein Ereignis abbrechbar ist, wird die `PreventDefault`‑Methode verwendet, um anzuzeigen, dass das Ereignis abgebrochen werden soll, was bedeutet, dass jede standardmäßige Aktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt wird, nicht stattfindet.

```java
public void PreventDefault()
```

## Hinweise

Wenn während irgendeiner Phase des Ereignisflusses die `PreventDefault`‑Methode aufgerufen wird, wird das Ereignis abgebrochen. Jede mit dem Ereignis verbundene Standardaktion findet nicht statt. Der Aufruf dieser Methode für ein nicht abbrechbares Ereignis hat keine Wirkung. Sobald `PreventDefault` aufgerufen wurde, bleibt sie für den Rest der Ereignispropagation wirksam. Diese Methode kann in jeder Phase des Ereignisflusses verwendet werden.

### Siehe auch

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
