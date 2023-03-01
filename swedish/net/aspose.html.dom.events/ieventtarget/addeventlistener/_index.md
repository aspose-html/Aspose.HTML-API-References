---
title: IEventTarget.AddEventListener
second_title: Aspose.HTML för .NET API Referens
description: IEventTarget metod. Denna metod tillåter registrering av händelseavlyssnare på händelsemålet.
type: docs
weight: 10
url: /sv/net/aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(string, IEventListener) {#addeventlistener}

Denna metod tillåter registrering av händelseavlyssnare på händelsemålet.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Händelsetypen som användaren registrerar sig för |
| listener | IEventListener | Tar ett gränssnitt implementerat av användaren som innehåller metoderna som ska anropas när händelsen inträffar. |

### Anmärkningar

Om en[`IEventListener`](../../ieventlistener/) läggs till en[`EventTarget`](../../../aspose.html.dom/eventtarget/) medan den bearbetar en händelse triggers den inte av de aktuella åtgärderna utan kan triggas under ett senare skede av händelseflödet, såsom bubblingsfasen.

Om flera identiska händelseavlyssnare är registrerade på samma[`EventTarget`](../../../aspose.html.dom/eventtarget/)med samma parametrar kasseras dubblettinstanserna. De orsakar inte[`IEventListener`](../../ieventlistener/) ska anropas två gånger och eftersom de kasseras behöver de inte tas bort med the [`RemoveEventListener`](../removeeventlistener/) metod.

### Se även

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namnutrymme [Aspose.Html.Dom.Events](../../ieventtarget/)
* hopsättning [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_1}

Denna metod tillåter registrering av händelseavlyssnare på händelsemålet.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Händelsetypen som användaren registrerar sig för |
| listener | IEventListener | Tar ett gränssnitt implementerat av användaren som innehåller metoderna som ska anropas när händelsen inträffar. |
| useCapture | Boolean | Om sant, anger useCapture att användaren vill initiera infångning. Efter att ha initierat infångning kommer alla händelser av den angivna typen att skickas till registered [`IEventListener`](../../ieventlistener/) innan de skickas till några händelsemål under dem i trädet. Händelser som bubblar uppåt genom trädet kommer inte att utlösa en[`IEventListener`](../../ieventlistener/) avsedd att använda infångning. |

### Anmärkningar

Om en[`IEventListener`](../../ieventlistener/) läggs till en[`EventTarget`](../../../aspose.html.dom/eventtarget/) medan den bearbetar en händelse triggers den inte av de aktuella åtgärderna utan kan triggas under ett senare skede av händelseflödet, såsom bubblingsfasen.

Om flera identiska händelseavlyssnare är registrerade på samma[`EventTarget`](../../../aspose.html.dom/eventtarget/)med samma parametrar kasseras dubblettinstanserna. De orsakar inte[`IEventListener`](../../ieventlistener/) ska anropas två gånger och eftersom de kasseras behöver de inte tas bort med the [`RemoveEventListener`](../removeeventlistener/) metod.

### Se även

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namnutrymme [Aspose.Html.Dom.Events](../../ieventtarget/)
* hopsättning [Aspose.HTML](../../../)


