---
title: IEventTarget.RemoveEventListener
second_title: Aspose.HTML för .NET API Referens
description: IEventTarget metod. Denna metod tillåter att händelseavlyssnare tas bort från händelsemålet. Om enIEventListener tas bort från enEventTarget medan den bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de tagits bort.
type: docs
weight: 30
url: /sv/net/aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(string, IEventListener) {#removeeventlistener}

Denna metod tillåter att händelseavlyssnare tas bort från händelsemålet. Om en[`IEventListener`](../../ieventlistener/) tas bort från en[`EventTarget`](../../../aspose.html.dom/eventtarget/) medan den bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de tagits bort.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Anger händelsetypen för[`IEventListener`](../../ieventlistener/) tas bort. |
| listener | IEventListener | De[`IEventListener`](../../ieventlistener/) parameter indikerar[`IEventListener`](../../ieventlistener/) ska tas bort. |

### Se även

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namnutrymme [Aspose.Html.Dom.Events](../../ieventtarget/)
* hopsättning [Aspose.HTML](../../../)

---

## RemoveEventListener(string, IEventListener, bool) {#removeeventlistener_1}

Denna metod tillåter att händelseavlyssnare tas bort från händelsemålet. Om en[`IEventListener`](../../ieventlistener/) tas bort från en[`EventTarget`](../../../aspose.html.dom/eventtarget/) medan den bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de tagits bort.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Anger händelsetypen för[`IEventListener`](../../ieventlistener/) tas bort. |
| listener | IEventListener | De[`IEventListener`](../../ieventlistener/) parameter indikerar[`IEventListener`](../../ieventlistener/) ska tas bort. |
| useCapture | Boolean | Anger om EventListener som tas bort har registrerats som en infångande lyssnare eller inte. Om en lyssnare registrerades två gånger, en med infångning och en utan, måste var och en tas bort separat. Borttagning av en infångande lyssnare påverkar inte en icke-fångande version av samma lyssnare och vice versa. |

### Se även

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namnutrymme [Aspose.Html.Dom.Events](../../ieventtarget/)
* hopsättning [Aspose.HTML](../../../)


