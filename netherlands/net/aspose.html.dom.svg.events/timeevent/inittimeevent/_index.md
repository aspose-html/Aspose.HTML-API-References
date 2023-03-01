---
title: TimeEvent.InitTimeEvent
second_title: Aspose.HTML voor .NET API-referentie
description: TimeEvent methode. De methode initTimeEvent wordt gebruikt om de waarde te initialiseren van een TimeEvent die via de DocumentEventinterface is gemaakt. Deze methode mag alleen worden aangeroepen voordat de TimeEvent is verzonden via de methode dispatchEvent hoewel deze tijdens die fase indien nodig meerdere keren kan worden aangeroepen. Als u meerdere keren wordt aangeroepen heeft de laatste aanroep voorrang.
type: docs
weight: 30
url: /nl/net/aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

De methode initTimeEvent wordt gebruikt om de waarde te initialiseren van een TimeEvent die via de DocumentEvent-interface is gemaakt. Deze methode mag alleen worden aangeroepen voordat de TimeEvent is verzonden via de methode dispatchEvent, hoewel deze tijdens die fase indien nodig meerdere keren kan worden aangeroepen. Als u meerdere keren wordt aangeroepen, heeft de laatste aanroep voorrang.

```csharp
public void InitTimeEvent(string typeArg, IAbstractView viewArg, long detailArg)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeArg | String | Specificeert het gebeurtenistype. |
| viewArg | IAbstractView | Specificeert de AbstractView van de gebeurtenis. |
| detailArg | Int64 | Specificeert de details van de gebeurtenis. |

### Zie ook

* interface [IAbstractView](../../../aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* naamruimte [Aspose.Html.Dom.Svg.Events](../../timeevent/)
* montage [Aspose.HTML](../../../)


