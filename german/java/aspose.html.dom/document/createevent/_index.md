---
title: "Document.CreateEvent"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Document-Methode. Erstellt ein Event eines von der Implementierung unterstützten Typs."
type: docs

url: /de/java/com.aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

Erstellt ein [`Event`](../../../com.aspose.html.dom.events/event/) eines von der Implementierung unterstützten Typs.

```java
public Event CreateEvent(String eventType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| eventType | String | Der Parameter eventType gibt den Typ der zu erstellenden [`Event`](../../../com.aspose.html.dom.events/event/)‑Schnittstelle an. Wenn die angegebene [`Event`](../../../com.aspose.html.dom.events/event/)‑Schnittstelle von der Implementierung unterstützt wird, gibt diese Methode ein neues [`Event`](../../../com.aspose.html.dom.events/event/) des angeforderten Schnittstellentyps zurück. Sollte das [`Event`](../../../com.aspose.html.dom.events/event/) über die Methode [`DispatchEvent`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) gesendet werden, muss nach der Erstellung die entsprechende [`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/)-Methode aufgerufen werden, um die Werte des [`Event`](../../../com.aspose.html.dom.events/event/) zu initialisieren. |

### Rückgabewert

Das neu erstellte [`Event`](../../../com.aspose.html.dom.events/event/)

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn die Implementierung den angeforderten Typ der [`Event`](../../../com.aspose.html.dom.events/event/) Schnittstelle nicht unterstützt |

### Siehe auch

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
