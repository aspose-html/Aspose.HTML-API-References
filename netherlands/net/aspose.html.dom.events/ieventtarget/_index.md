---
title: Interface IEventTarget
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Events.IEventTarget koppel. DeEventTarget interface wordt geïmplementeerd door alle Nodes in een implementatie die het DOM Event Model ondersteunt. Daarom kan deze interface worden verkregen door bindingspecifieke castingmethoden te gebruiken op een instantie van de Nodeinterface. De interface maakt registratie en verwijdering van Event Listeners op eenEventTarget en verzending van gebeurtenissen daarnaartoeIEventTarget .
type: docs
weight: 810
url: /nl/net/aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

De[`EventTarget`](../../aspose.html.dom/eventtarget/) interface wordt geïmplementeerd door alle Nodes in een implementatie die het DOM Event Model ondersteunt. Daarom kan deze interface worden verkregen door bindingspecifieke castingmethoden te gebruiken op een instantie van de Node-interface. De interface maakt registratie en verwijdering van Event Listeners op een[`EventTarget`](../../aspose.html.dom/eventtarget/) en verzending van gebeurtenissen daarnaartoe`IEventTarget` .

```csharp
public interface IEventTarget
```

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(string, IEventListener) | Met deze methode kunnen gebeurtenislisteners worden geregistreerd op het gebeurtenisdoel. |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener, bool) | Met deze methode kunnen gebeurtenislisteners worden geregistreerd op het gebeurtenisdoel. |
| [DispatchEvent](../../aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Met deze methode kunnen gebeurtenissen worden verzonden naar het gebeurtenismodel van de implementatie. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(string, IEventListener) | Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../ieventlistener/) wordt verwijderd uit een[`EventTarget`](../../aspose.html.dom/eventtarget/) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener, bool) | Met deze methode kunnen gebeurtenislisteners uit het gebeurtenisdoel worden verwijderd. Als een[`IEventListener`](../ieventlistener/) wordt verwijderd uit een[`EventTarget`](../../aspose.html.dom/eventtarget/) terwijl het een gebeurtenis verwerkt, wordt het niet geactiveerd door de huidige acties. Gebeurtenislisteners kunnen nooit worden aangeroepen nadat ze zijn verwijderd. |

### Zie ook

* naamruimte [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* montage [Aspose.HTML](../../)


