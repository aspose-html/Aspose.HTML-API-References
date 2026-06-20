---
title: "IDocumentEvent.CreateEvent"
second_title: "Aspose.HTML für Java API-Referenz"
description: "IDocumentEvent-Methode. Die createEvent-Methode wird verwendet, um Events zu erstellen, wenn es für den Benutzer entweder unpraktisch oder unnötig ist, ein Event selbst zu erstellen."
type: docs

url: /de/java/com.aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Die Methode createEvent wird zur Erstellung von Ereignissen verwendet, wenn es für den Benutzer unpraktisch oder unnötig ist, ein Ereignis selbst zu erstellen.

```java
public Event CreateEvent(String eventType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| eventType | String | Der eventType-Parameter gibt den Typ des zu erstellenden Interfaces an. Wenn das angegebene Interface von der Implementierung unterstützt wird, gibt diese Methode ein neues Objekt des angeforderten Interface-Typs zurück. Wenn das über die Methode zu dispatchende ist, muss nach der Erstellung die entsprechende Methode aufgerufen werden, um die Werte zu initialisieren. Die Methode wird verwendet, um s zu erstellen, wenn es für den Benutzer entweder unpraktisch oder unnötig ist, ein s selbst zu erstellen. In Fällen, in denen die von der Implementierung bereitgestellte Implementierung unzureichend ist, können Benutzer ihre eigenen Implementierungen für die Verwendung mit der Methode bereitstellen. |

### Rückgabewert

Gibt das neu erstellte Event des angegebenen Ereignistyps zurück.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn die Implementierung den angeforderten Interface-Typ nicht unterstützt |

### Siehe auch

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
