---
title: IEventTarget.AddEventListener
second_title: Aspose.HTML für .NET-API-Referenz
description: IEventTarget methode. Diese Methode ermöglicht die Registrierung von EreignisListenern auf dem Ereignisziel.
type: docs
weight: 10
url: /de/net/aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(string, IEventListener) {#addeventlistener}

Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Der Ereignistyp, für den sich der Benutzer anmeldet |
| listener | IEventListener | Akzeptiert eine vom Benutzer implementierte Schnittstelle, die die aufzurufenden Methoden enthält, wenn das Ereignis eintritt. |

### Bemerkungen

Wenn ein[`IEventListener`](../../ieventlistener/) wird zu einem hinzugefügt[`EventTarget`](../../../aspose.html.dom/eventtarget/) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst , kann aber in einer späteren Phase des Ereignisablaufs ausgelöst werden, wie z. B. in der Bubbling-Phase.

Wenn mehrere identische Ereignis-Listener auf demselben registriert sind[`EventTarget`](../../../aspose.html.dom/eventtarget/)mit den gleichen Parametern werden die doppelten Instanzen verworfen. Sie verursachen das nicht[`IEventListener`](../../ieventlistener/) zweimal aufgerufen werden und da sie verworfen werden, müssen sie nicht mit the entfernt werden[`RemoveEventListener`](../removeeventlistener/) Methode.

### Siehe auch

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namensraum [Aspose.Html.Dom.Events](../../ieventtarget/)
* Montage [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_1}

Diese Methode ermöglicht die Registrierung von Ereignis-Listenern auf dem Ereignisziel.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Der Ereignistyp, für den sich der Benutzer anmeldet |
| listener | IEventListener | Akzeptiert eine vom Benutzer implementierte Schnittstelle, die die aufzurufenden Methoden enthält, wenn das Ereignis eintritt. |
| useCapture | Boolean | Wenn wahr, zeigt useCapture an, dass der Benutzer die Erfassung initiieren möchte. Nach der Initiierung der Erfassung werden alle Ereignisse des angegebenen Typs an den registrierten gesendet.[`IEventListener`](../../ieventlistener/) , bevor sie an irgendwelche Ereignisziele unter ihnen im Baum gesendet werden. Ereignisse, die durch den Baum nach oben sprudeln, lösen keine aus[`IEventListener`](../../ieventlistener/) für die Erfassung bestimmt. |

### Bemerkungen

Wenn ein[`IEventListener`](../../ieventlistener/) wird zu einem hinzugefügt[`EventTarget`](../../../aspose.html.dom/eventtarget/) während es ein Ereignis verarbeitet, wird es nicht durch die aktuellen Aktionen ausgelöst , kann aber in einer späteren Phase des Ereignisablaufs ausgelöst werden, wie z. B. in der Bubbling-Phase.

Wenn mehrere identische Ereignis-Listener auf demselben registriert sind[`EventTarget`](../../../aspose.html.dom/eventtarget/)mit den gleichen Parametern werden die doppelten Instanzen verworfen. Sie verursachen das nicht[`IEventListener`](../../ieventlistener/) zweimal aufgerufen werden und da sie verworfen werden, müssen sie nicht mit the entfernt werden[`RemoveEventListener`](../removeeventlistener/) Methode.

### Siehe auch

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namensraum [Aspose.Html.Dom.Events](../../ieventtarget/)
* Montage [Aspose.HTML](../../../)


