---
title: Interface IEventListener
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Events.IEventListener gränssnitt. DenIEventListenergränssnittet är den primära metoden för att hantera händelser. Användare implementerarIEventListener gränssnitt och registrera sin lyssnare på enEventTarget användaAddEventListener method. Användarna bör också ta bort sinaIEventListener från dessEventTarget efter att de har slutfört använda lyssnaren.
type: docs
weight: 800
url: /sv/net/aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

Den`IEventListener`gränssnittet är den primära metoden för att hantera händelser. Användare implementerar`IEventListener` gränssnitt och registrera sin lyssnare på en[`EventTarget`](../../aspose.html.dom/eventtarget/) använda[`AddEventListener`](../../aspose.html.dom/eventtarget/addeventlistener/) method. Användarna bör också ta bort sina`IEventListener` från dess[`EventTarget`](../../aspose.html.dom/eventtarget/) efter att de har slutfört använda lyssnaren.

```csharp
public interface IEventListener
```

## Metoder

| namn | Beskrivning |
| --- | --- |
| [HandleEvent](../../aspose.html.dom.events/ieventlistener/handleevent/)(Event) | Denna metod anropas närhelst en händelse inträffar av den typ för vilken`IEventListener` gränssnittet registrerades. |

### Anmärkningar

När en Nod kopieras med metoden cloneNode kopplas inte händelseavlyssnare som är kopplade till källnoden till den kopierade noden. Om användaren vill att samma händelseavlyssnare ska läggas till i den nyskapade kopian måste användaren lägga till dem manuellt.

### Se även

* namnutrymme [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* hopsättning [Aspose.HTML](../../)


