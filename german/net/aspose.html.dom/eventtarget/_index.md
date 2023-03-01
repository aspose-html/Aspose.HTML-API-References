---
title: Class EventTarget
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.EventTarget klas. DieEventTarget Schnittstelle wird von allen Knoten in einer Implementierung implementiert die das DOMEreignismodell unterstützt. Daher kann diese Schnittstelle durch Verwendung bindungsspezifischer CastingMethoden auf einer Instanz der Knotenschnittstelle erhalten werden. Die Schnittstelle ermöglicht die Registrierung und Entfernung von EreignisListenern einEventTarget und Versand von Ereignissen dazuIEventTarget .
type: docs
weight: 720
url: /de/net/aspose.html.dom/eventtarget/
---
## EventTarget class

Die`EventTarget` -Schnittstelle wird von allen Knoten in einer Implementierung implementiert, die das DOM-Ereignismodell unterstützt. Daher kann diese Schnittstelle durch Verwendung bindungsspezifischer Casting-Methoden auf einer Instanz der Knotenschnittstelle erhalten werden. Die Schnittstelle ermöglicht die Registrierung und Entfernung von Ereignis-Listenern ein`EventTarget` und Versand von Ereignissen dazu[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) .

```csharp
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener) | Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(string, DOMEventHandler, bool) | Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(string, IEventListener, bool) | Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Diese Methode ermöglicht die Weiterleitung von Ereignissen in das Ereignismodell der Implementierung. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Führt anwendungsdefinierte Aufgaben aus, die mit dem Freigeben, Freigeben oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener) | Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) wird aus einem entfernt`EventTarget` während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(string, DOMEventHandler, bool) | Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) wird aus einem entfernt`EventTarget` während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(string, IEventListener, bool) | Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) wird aus einem entfernt`EventTarget` während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden. |

### Siehe auch

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* namensraum [Aspose.Html.Dom](../../aspose.html.dom/)
* Montage [Aspose.HTML](../../)


