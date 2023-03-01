---
title: Event.InitEvent
second_title: Aspose.HTML för .NET API Referens
description: Event metod. DenInitEvent metod används för att initiera värdet av enEvent skapad genom IDocumentEvent gränssnitt.
type: docs
weight: 110
url: /sv/net/aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

Den`InitEvent` metod används för att initiera värdet av en[`Event`](../) skapad genom [`IDocumentEvent`](../../idocumentevent/) gränssnitt.

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Händelsetypen. |
| bubbles | Boolean | om inställt på`Sann` [bubblor]. |
| cancelable | Boolean | om inställt på`Sann` [avbrytbar]. |

### Anmärkningar

Denna metod får endast anropas innan händelsen har skickats via[`DispatchEvent`](../../ieventtarget/dispatchevent/) metod, även om den kan anropas flera gånger under den fasen om det behövs. Om det anropas flera gånger har den slutliga anropet företräde. Om det anropas från en underklass av Event-gränssnittet ändras endast de värden som anges i initEvent-metoden, alla andra attribut lämnas oförändrade.

### Se även

* class [Event](../)
* namnutrymme [Aspose.Html.Dom.Events](../../event/)
* hopsättning [Aspose.HTML](../../../)


