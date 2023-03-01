---
title: Event.PreventDefault
second_title: Aspose.HTML för .NET API Referens
description: Event metod. Om en händelse kan avbrytasPreventDefault metod används för att indikera att händelsen ska avbrytas vilket betyder att någon standardåtgärd som normalt vidtas av implementeringen som ett resultat av händelsen inte kommer att inträffa.
type: docs
weight: 120
url: /sv/net/aspose.html.dom.events/event/preventdefault/
---
## Event.PreventDefault method

Om en händelse kan avbrytas,`PreventDefault` metod används för att indikera att händelsen ska avbrytas, vilket betyder att någon standardåtgärd som normalt vidtas av implementeringen som ett resultat av händelsen inte kommer att inträffa.

```csharp
public void PreventDefault()
```

### Anmärkningar

Om, under något skede av händelseflödet,`PreventDefault`metoden kallas händelsen avbryts. Alla standardåtgärder associerade med händelsen kommer inte att inträffa. Att anropa den här metoden för en icke-avbrytbar händelse har ingen effekt. Once`PreventDefault` har kallats kommer den att förbli i kraft under resten av händelsens utbredning. Denna metod kan användas under alla skeden av händelseflödet.

### Se även

* class [Event](../)
* namnutrymme [Aspose.Html.Dom.Events](../../event/)
* hopsättning [Aspose.HTML](../../../)


