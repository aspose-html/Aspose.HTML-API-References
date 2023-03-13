---
title: EventTarget.AddEventListener
second_title: Aspose.HTML för .NET API Referens
description: EventTarget metod. Denna metod tillåter registrering av händelseavlyssnare på händelsemålet.
type: docs
weight: 10
url: /sv/net/aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(string, DOMEventHandler, bool) {#addeventlistener}

Denna metod tillåter registrering av händelseavlyssnare på händelsemålet.

```csharp
public void AddEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Händelsetypen som användaren registrerar sig för |
| handler | DOMEventHandler | Tar en[`DOMEventHandler`](../../../aspose.html.dom.events/domeventhandler/) att ringas upp när händelsen inträffar. |
| useCapture | Boolean | Om sant, anger useCapture att användaren vill initiera infångning. Efter att ha initierat infångning kommer alla händelser av den angivna typen att skickas till registered [`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) innan de skickas till några händelsemål under dem i trädet. Händelser som bubblar uppåt genom trädet kommer inte att utlösa en[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) avsedd att använda infångning. |

### Anmärkningar

Om en[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) läggs till en[`EventTarget`](../) medan den bearbetar en händelse triggers den inte av de aktuella åtgärderna utan kan triggas under ett senare skede av händelseflödet, såsom bubblingsfasen.

Om flera identiska händelseavlyssnare är registrerade på samma[`EventTarget`](../)med samma parametrar kasseras dubblettinstanserna. De orsakar inte[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) ska anropas två gånger och eftersom de kasseras behöver de inte tas bort med the [`RemoveEventListener`](../removeeventlistener/) metod.

### Se även

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* namnutrymme [Aspose.Html.Dom](../../eventtarget/)
* hopsättning [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener) {#addeventlistener_1}

Denna metod tillåter registrering av händelseavlyssnare på händelsemålet.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Händelsetypen som användaren registrerar sig för |
| listener | IEventListener | Tar ett gränssnitt implementerat av användaren som innehåller metoderna som ska anropas när händelsen inträffar. |

### Anmärkningar

Om en[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) läggs till en[`EventTarget`](../) medan den bearbetar en händelse triggers den inte av de aktuella åtgärderna utan kan triggas under ett senare skede av händelseflödet, såsom bubblingsfasen.

Om flera identiska händelseavlyssnare är registrerade på samma[`EventTarget`](../)med samma parametrar kasseras dubblettinstanserna. De orsakar inte[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) ska anropas två gånger och eftersom de kasseras behöver de inte tas bort med the [`RemoveEventListener`](../removeeventlistener/) metod.

### Se även

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* namnutrymme [Aspose.Html.Dom](../../eventtarget/)
* hopsättning [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_2}

Denna metod tillåter registrering av händelseavlyssnare på händelsemålet.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Händelsetypen som användaren registrerar sig för |
| listener | IEventListener | Tar ett gränssnitt implementerat av användaren som innehåller metoderna som ska anropas när händelsen inträffar. |
| useCapture | Boolean | Om sant, anger useCapture att användaren vill initiera infångning. Efter att ha initierat infångning kommer alla händelser av den angivna typen att skickas till registered [`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) innan de skickas till några händelsemål under dem i trädet. Händelser som bubblar uppåt genom trädet kommer inte att utlösa en[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) avsedd att använda infångning. |

### Anmärkningar

Om en[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) läggs till en[`EventTarget`](../) medan den bearbetar en händelse triggers den inte av de aktuella åtgärderna utan kan triggas under ett senare skede av händelseflödet, såsom bubblingsfasen.

Om flera identiska händelseavlyssnare är registrerade på samma[`EventTarget`](../)med samma parametrar kasseras dubblettinstanserna. De orsakar inte[`IEventListener`](../../../aspose.html.dom.events/ieventlistener/) ska anropas två gånger och eftersom de kasseras behöver de inte tas bort med the [`RemoveEventListener`](../removeeventlistener/) metod.

### Se även

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* namnutrymme [Aspose.Html.Dom](../../eventtarget/)
* hopsättning [Aspose.HTML](../../../)


