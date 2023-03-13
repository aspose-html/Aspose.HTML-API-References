---
title: EventTarget.RemoveEventListener
second_title: Aspose.HTML voor .NET API-referentie
description: EventTarget methode. Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als eenIEventListener wordt verwijderd uit eenEventTarget terwijl het een gebeurtenis verwerkt wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd.
type: docs
weight: 40
url: /nl/net/aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(string, DOMEventHandler, bool) {#removeeventlistener}

Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) wordt verwijderd uit een[`EventTarget`](../) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Specificeert het gebeurtenistype van het[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) wordt verwijderd. |
| handler | DOMEventHandler | De[`DOMEventHandler`](../../../aspose.html.dom.events/domeventhandler/) parameter geeft de[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) verwijderd worden. |
| useCapture | Boolean | Geeft aan of de EventListener die wordt verwijderd, al dan niet is geregistreerd als vastleggende luisteraar. Als een luisteraar twee keer is geregistreerd, één met vastleggen en één zonder, moet elke luisteraar afzonderlijk worden verwijderd. Het verwijderen van een vastleggende luisteraar heeft geen invloed op een niet-vastleggende versie van dezelfde luisteraar, en vice versa. |

### Zie ook

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* naamruimte [Aspose.Html.Dom](../../eventtarget/)
* montage [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener) {#removeeventlistener_1}

Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) wordt verwijderd uit een[`EventTarget`](../) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Specificeert het gebeurtenistype van het[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) wordt verwijderd. |
| listener | IEventListener | De[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) parameter geeft de[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) verwijderd worden. |

### Zie ook

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* naamruimte [Aspose.Html.Dom](../../eventtarget/)
* montage [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_2}

Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) wordt verwijderd uit een[`EventTarget`](../) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Specificeert het gebeurtenistype van het[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) wordt verwijderd. |
| listener | IEventListener | De[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) parameter geeft de[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) verwijderd worden. |
| useCapture | Boolean | Geeft aan of de EventListener die wordt verwijderd, al dan niet is geregistreerd als vastleggende luisteraar. Als een luisteraar twee keer is geregistreerd, één met vastleggen en één zonder, moet elke luisteraar afzonderlijk worden verwijderd. Het verwijderen van een vastleggende luisteraar heeft geen invloed op een niet-vastleggende versie van dezelfde luisteraar, en vice versa. |

### Zie ook

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* naamruimte [Aspose.Html.Dom](../../eventtarget/)
* montage [Aspose.HTML](../../../)


