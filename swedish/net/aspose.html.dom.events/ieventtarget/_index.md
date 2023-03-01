---
title: Interface IEventTarget
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Events.IEventTarget gränssnitt. DenEventTarget gränssnitt implementeras av alla noder i en implementering som stöder DOMhändelsemodellen. Därför kan detta gränssnitt erhållas genom att använda bindningsspecifika castingmetoder på en instans av nodgränssnittet. Gränssnittet tillåter registrering och borttagning av händelseavlyssnare på enEventTarget och sändning av händelser till detIEventTarget .
type: docs
weight: 810
url: /sv/net/aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

Den[`EventTarget`](../../aspose.html.dom/eventtarget/) gränssnitt implementeras av alla noder i en implementering som stöder DOM-händelsemodellen. Därför kan detta gränssnitt erhållas genom att använda bindningsspecifika castingmetoder på en instans av nodgränssnittet. Gränssnittet tillåter registrering och borttagning av händelseavlyssnare på en[`EventTarget`](../../aspose.html.dom/eventtarget/) och sändning av händelser till det`IEventTarget` .

```csharp
public interface IEventTarget
```

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(string, IEventListener) | Denna metod tillåter registrering av händelseavlyssnare på händelsemålet. |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener, bool) | Denna metod tillåter registrering av händelseavlyssnare på händelsemålet. |
| [DispatchEvent](../../aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Denna metod tillåter sändning av händelser till implementeringshändelsemodellen. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(string, IEventListener) | Denna metod tillåter att händelseavlyssnare tas bort från händelsemålet. Om en[`IEventListener`](../ieventlistener/) tas bort från en[`EventTarget`](../../aspose.html.dom/eventtarget/) medan den bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de tagits bort. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener, bool) | Denna metod tillåter att händelseavlyssnare tas bort från händelsemålet. Om en[`IEventListener`](../ieventlistener/) tas bort från en[`EventTarget`](../../aspose.html.dom/eventtarget/) medan den bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de tagits bort. |

### Se även

* namnutrymme [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* hopsättning [Aspose.HTML](../../)


