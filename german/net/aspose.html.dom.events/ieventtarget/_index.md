---
title: Interface IEventTarget
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.Events.IEventTarget koppel. DieEventTarget Schnittstelle wird von allen Knoten in einer Implementierung implementiert die das DOMEreignismodell unterstützt. Daher kann diese Schnittstelle durch Verwendung bindungsspezifischer CastingMethoden auf einer Instanz der Knotenschnittstelle erhalten werden. Die Schnittstelle ermöglicht die Registrierung und Entfernung von EreignisListenern einEventTarget und Versand von Ereignissen dazuIEventTarget .
type: docs
weight: 810
url: /de/net/aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

Die[`EventTarget`](../../aspose.html.dom/eventtarget/) -Schnittstelle wird von allen Knoten in einer Implementierung implementiert, die das DOM-Ereignismodell unterstützt. Daher kann diese Schnittstelle durch Verwendung bindungsspezifischer Casting-Methoden auf einer Instanz der Knotenschnittstelle erhalten werden. Die Schnittstelle ermöglicht die Registrierung und Entfernung von Ereignis-Listenern ein[`EventTarget`](../../aspose.html.dom/eventtarget/) und Versand von Ereignissen dazu`IEventTarget` .

```csharp
public interface IEventTarget
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(string, IEventListener) | Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel. |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener, bool) | Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel. |
| [DispatchEvent](../../aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Diese Methode ermöglicht die Weiterleitung von Ereignissen in das Ereignismodell der Implementierung. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(string, IEventListener) | Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../ieventlistener/) wird aus einem entfernt[`EventTarget`](../../aspose.html.dom/eventtarget/) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener, bool) | Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../ieventlistener/) wird aus einem entfernt[`EventTarget`](../../aspose.html.dom/eventtarget/) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden. |

### Siehe auch

* namensraum [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* Montage [Aspose.HTML](../../)


