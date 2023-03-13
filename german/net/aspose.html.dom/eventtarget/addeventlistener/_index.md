---
title: EventTarget.AddEventListener
second_title: Aspose.HTML für .NET-API-Referenz
description: EventTarget methode. Diese Methode ermöglicht die Registrierung von EreignisListenern auf dem Ereignisziel.
type: docs
weight: 10
url: /de/net/aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(string, DOMEventHandler, bool) {#addeventlistener}

Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel.

```csharp
public void AddEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Der Ereignistyp, für den sich der Benutzer anmeldet |
| handler | DOMEventHandler | Dauert ein[`DOMEventHandler`](../../../aspose.html.dom.events/domeventhandler/) angerufen werden, wenn das Ereignis eintritt. |
| useCapture | Boolean | Wenn wahr, zeigt useCapture an, dass der Benutzer die Erfassung initiieren möchte. Nach der Initiierung der Erfassung werden alle Ereignisse des angegebenen Typs an den registrierten gesendet.[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) , bevor sie an irgendwelche Ereignisziele unter ihnen im Baum gesendet werden. Ereignisse, die durch den Baum nach oben sprudeln, lösen keine aus[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) für die Erfassung bestimmt. |

### Bemerkungen

Wenn ein[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) wird zu einem hinzugefügt[`EventTarget`](../) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst , kann aber in einer späteren Phase des Ereignisablaufs ausgelöst werden, wie z. B. in der Bubbling-Phase.

Wenn mehrere identische Ereignis-Listener auf demselben registriert sind[`EventTarget`](../)mit den gleichen Parametern werden die doppelten Instanzen verworfen. Sie verursachen das nicht[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) zweimal aufgerufen werden und da sie verworfen werden, müssen sie nicht mit the entfernt werden[`RemoveEventListener`](../removeeventlistener/) Methode.

### Siehe auch

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* namensraum [Aspose.Html.Dom](../../eventtarget/)
* Montage [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener) {#addeventlistener_1}

Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Der Ereignistyp, für den sich der Benutzer anmeldet |
| listener | IEventListener | Akzeptiert eine vom Benutzer implementierte Schnittstelle, die die aufzurufenden Methoden enthält, wenn das Ereignis eintritt. |

### Bemerkungen

Wenn ein[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) wird zu einem hinzugefügt[`EventTarget`](../) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst , kann aber in einer späteren Phase des Ereignisablaufs ausgelöst werden, wie z. B. in der Bubbling-Phase.

Wenn mehrere identische Ereignis-Listener auf demselben registriert sind[`EventTarget`](../)mit den gleichen Parametern werden die doppelten Instanzen verworfen. Sie verursachen das nicht[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) zweimal aufgerufen werden und da sie verworfen werden, müssen sie nicht mit the entfernt werden[`RemoveEventListener`](../removeeventlistener/) Methode.

### Siehe auch

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* namensraum [Aspose.Html.Dom](../../eventtarget/)
* Montage [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_2}

Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Der Ereignistyp, für den sich der Benutzer anmeldet |
| listener | IEventListener | Akzeptiert eine vom Benutzer implementierte Schnittstelle, die die aufzurufenden Methoden enthält, wenn das Ereignis eintritt. |
| useCapture | Boolean | Wenn wahr, zeigt useCapture an, dass der Benutzer die Erfassung initiieren möchte. Nach der Initiierung der Erfassung werden alle Ereignisse des angegebenen Typs an den registrierten gesendet.[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) , bevor sie an irgendwelche Ereignisziele unter ihnen im Baum gesendet werden. Ereignisse, die durch den Baum nach oben sprudeln, lösen keine aus[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) für die Erfassung bestimmt. |

### Bemerkungen

Wenn ein[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) wird zu einem hinzugefügt[`EventTarget`](../) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst , kann aber in einer späteren Phase des Ereignisablaufs ausgelöst werden, wie z. B. in der Bubbling-Phase.

Wenn mehrere identische Ereignis-Listener auf demselben registriert sind[`EventTarget`](../)mit den gleichen Parametern werden die doppelten Instanzen verworfen. Sie verursachen das nicht[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) zweimal aufgerufen werden und da sie verworfen werden, müssen sie nicht mit the entfernt werden[`RemoveEventListener`](../removeeventlistener/) Methode.

### Siehe auch

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* namensraum [Aspose.Html.Dom](../../eventtarget/)
* Montage [Aspose.HTML](../../../)


