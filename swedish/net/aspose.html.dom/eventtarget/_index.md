---
title: Class EventTarget
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.EventTarget klass. DenEventTarget gränssnitt implementeras av alla noder i en implementering som stöder DOMhändelsemodellen. Därför kan detta gränssnitt erhållas genom att använda bindningsspecifika castingmetoder på en instans av nodgränssnittet. Gränssnittet tillåter registrering och borttagning av händelseavlyssnare på enEventTarget och sändning av händelser till detIEventTarget .
type: docs
weight: 720
url: /sv/net/aspose.html.dom/eventtarget/
---
## EventTarget class

Den`EventTarget` gränssnitt implementeras av alla noder i en implementering som stöder DOM-händelsemodellen. Därför kan detta gränssnitt erhållas genom att använda bindningsspecifika castingmetoder på en instans av nodgränssnittet. Gränssnittet tillåter registrering och borttagning av händelseavlyssnare på en`EventTarget` och sändning av händelser till det[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) .

```csharp
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener) | Denna metod tillåter registrering av händelseavlyssnare på händelsemålet. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(string, DOMEventHandler, bool) | Denna metod tillåter registrering av händelseavlyssnare på händelsemålet. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(string, IEventListener, bool) | Denna metod tillåter registrering av händelseavlyssnare på händelsemålet. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Denna metod tillåter sändning av händelser till implementeringshändelsemodellen. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Utför programdefinierade uppgifter associerade med att frigöra, frigöra eller återställa ohanterade resurser. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener) | Denna metod tillåter att händelseavlyssnare tas bort från händelsemålet. Om en[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) tas bort från en`EventTarget` medan den bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de tagits bort. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(string, DOMEventHandler, bool) | Denna metod tillåter att händelseavlyssnare tas bort från händelsemålet. Om en[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) tas bort från en`EventTarget` medan den bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de tagits bort. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(string, IEventListener, bool) | Denna metod tillåter att händelseavlyssnare tas bort från händelsemålet. Om en[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) tas bort från en`EventTarget` medan den bearbetar en händelse kommer den inte att utlösas av de aktuella åtgärderna. Händelselyssnare kan aldrig anropas efter att de tagits bort. |

### Se även

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* namnutrymme [Aspose.Html.Dom](../../aspose.html.dom/)
* hopsättning [Aspose.HTML](../../)


