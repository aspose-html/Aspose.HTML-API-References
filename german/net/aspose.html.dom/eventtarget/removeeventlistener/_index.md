---
title: EventTarget.RemoveEventListener
second_title: Aspose.HTML für .NET-API-Referenz
description: EventTarget methode. Diese Methode ermöglicht das Entfernen von EreignisListenern aus dem Ereignisziel. Wenn anIEventListener wird aus einem entferntEventTarget während es ein Ereignis verarbeitet wird es nicht durch die aktuellen Aktionen ausgelöst. EreignisListener können nie aufgerufen werden nachdem sie entfernt wurden.
type: docs
weight: 40
url: /de/net/aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(string, DOMEventHandler, bool) {#removeeventlistener}

Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) wird aus einem entfernt[`EventTarget`](../) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Gibt den Ereignistyp der an[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) entfernt werden. |
| handler | DOMEventHandler | Der[`DOMEventHandler`](../../../aspose.html.dom.events/domeventhandler/) Parameter gibt die an[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) entfernt werden. |
| useCapture | Boolean | Gibt an, ob der zu entfernende EventListener als erfassender Listener registriert wurde oder nicht. Wenn ein Listener zweimal registriert wurde, einer mit Erfassung und einer ohne, muss jeder separat entfernt werden. Das Entfernen eines erfassenden Listeners wirkt sich nicht auf eine nicht erfassende Version aus desselben Zuhörers und umgekehrt. |

### Siehe auch

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* namensraum [Aspose.Html.Dom](../../eventtarget/)
* Montage [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener) {#removeeventlistener_1}

Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) wird aus einem entfernt[`EventTarget`](../) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Gibt den Ereignistyp der an[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) entfernt werden. |
| listener | IEventListener | Der[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) Parameter gibt die an[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) entfernt werden. |

### Siehe auch

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* namensraum [Aspose.Html.Dom](../../eventtarget/)
* Montage [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_2}

Diese Methode ermöglicht das Entfernen von Ereignis-Listenern aus dem Ereignisziel. Wenn an[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) wird aus einem entfernt[`EventTarget`](../) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst. Ereignis-Listener können nie aufgerufen werden, nachdem sie entfernt wurden.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Gibt den Ereignistyp der an[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) entfernt werden. |
| listener | IEventListener | Der[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) Parameter gibt die an[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) entfernt werden. |
| useCapture | Boolean | Gibt an, ob der zu entfernende EventListener als erfassender Listener registriert wurde oder nicht. Wenn ein Listener zweimal registriert wurde, einer mit Erfassung und einer ohne, muss jeder separat entfernt werden. Das Entfernen eines erfassenden Listeners wirkt sich nicht auf eine nicht erfassende Version aus desselben Zuhörers und umgekehrt. |

### Siehe auch

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* namensraum [Aspose.Html.Dom](../../eventtarget/)
* Montage [Aspose.HTML](../../../)


