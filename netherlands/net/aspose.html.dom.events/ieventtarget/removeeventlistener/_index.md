---
title: IEventTarget.RemoveEventListener
second_title: Aspose.HTML voor .NET API-referentie
description: IEventTarget methode. Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als eenIEventListener wordt verwijderd uit eenEventTarget terwijl het een gebeurtenis verwerkt wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd.
type: docs
weight: 30
url: /nl/net/aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(string, IEventListener) {#removeeventlistener}

Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../../ieventlistener/) wordt verwijderd uit een[`EventTarget`](../../../aspose.html.dom/eventtarget/) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Specificeert het gebeurtenistype van het[`IEventListener`](../../ieventlistener/) wordt verwijderd. |
| listener | IEventListener | De[`IEventListener`](../../ieventlistener/) parameter geeft de[`IEventListener`](../../ieventlistener/) verwijderd worden. |

### Zie ook

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* naamruimte [Aspose.Html.Dom.Events](../../ieventtarget/)
* montage [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_1}

Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../../ieventlistener/) wordt verwijderd uit een[`EventTarget`](../../../aspose.html.dom/eventtarget/) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Specificeert het gebeurtenistype van het[`IEventListener`](../../ieventlistener/) wordt verwijderd. |
| listener | IEventListener | De[`IEventListener`](../../ieventlistener/) parameter geeft de[`IEventListener`](../../ieventlistener/) verwijderd worden. |
| useCapture | Boolean | Geeft aan of de EventListener die wordt verwijderd, al dan niet is geregistreerd als vastleggende luisteraar. Als een luisteraar twee keer is geregistreerd, één met vastleggen en één zonder, moet elke luisteraar afzonderlijk worden verwijderd. Het verwijderen van een vastleggende luisteraar heeft geen invloed op een niet-vastleggende versie van dezelfde luisteraar, en vice versa. |

### Zie ook

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* naamruimte [Aspose.Html.Dom.Events](../../ieventtarget/)
* montage [Aspose.HTML](../../../)


