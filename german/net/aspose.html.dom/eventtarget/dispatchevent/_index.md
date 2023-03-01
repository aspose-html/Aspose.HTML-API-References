---
title: EventTarget.DispatchEvent
second_title: Aspose.HTML für .NET-API-Referenz
description: EventTarget methode. Diese Methode ermöglicht die Weiterleitung von Ereignissen in das Ereignismodell der Implementierung.
type: docs
weight: 20
url: /de/net/aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Diese Methode ermöglicht die Weiterleitung von Ereignissen in das Ereignismodell der Implementierung.

```csharp
public bool DispatchEvent(Event @event)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| event | Event | Gibt den Ereignistyp, das Verhalten und die Kontextinformationen an, die bei der Verarbeitung des Ereignisses verwendet werden sollen. |

### Rückgabewert

Der Rückgabewert von`DispatchEvent` gibt an, ob einer der Listener, die das Ereignis behandelt haben, aufgerufen hat[`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/) . Wenn[`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/) aufgerufen wurde, ist der Wert falsch, sonst ist der Wert wahr.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../domexception/) |  |

### Bemerkungen

Auf diese Weise gesendete Ereignisse haben das gleiche Erfassungs- und Bubbling-Verhalten wie direkt von der Implementierung gesendete Ereignisse. Das Ziel des Ereignisses ist die[`EventTarget`](../) auf welche`DispatchEvent` heißt.

### Siehe auch

* class [Event](../../../aspose.html.dom.events/event/)
* class [EventTarget](../)
* namensraum [Aspose.Html.Dom](../../eventtarget/)
* Montage [Aspose.HTML](../../../)


