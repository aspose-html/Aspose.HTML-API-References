---
title: CustomEvent.InitCustomEvent
second_title: Aspose.HTML för .NET API Referens
description: CustomEvent metod. /// DenInitEvent metod används för att initiera värdet av enEvent skapas genomIDocumentEvent gränssnitt.
type: docs
weight: 30
url: /sv/net/aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// Den[`InitEvent`](../../event/initevent/) metod används för att initiera värdet av en[`Event`](../../event/) skapas genom[`IDocumentEvent`](../../idocumentevent/) gränssnitt.

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Händelsetypen. |
| bubbles | Boolean | om inställt på`Sann` [bubblor]. |
| cancelable | Boolean | om inställt på`Sann` [avbrytbar]. |
| detail | Object | De anpassade uppgifterna. |

### Anmärkningar

Denna metod får endast anropas innan händelsen har skickats via[`DispatchEvent`](../../ieventtarget/dispatchevent/) metod, även om den kan anropas flera gånger under den fasen om det behövs. Om det anropas flera gånger har den slutliga anropet företräde. Om det anropas från en underklass av Event-gränssnittet ändras endast de värden som anges i initEvent-metoden, alla andra attribut lämnas oförändrade.

### Se även

* class [CustomEvent](../)
* namnutrymme [Aspose.Html.Dom.Events](../../customevent/)
* hopsättning [Aspose.HTML](../../../)


