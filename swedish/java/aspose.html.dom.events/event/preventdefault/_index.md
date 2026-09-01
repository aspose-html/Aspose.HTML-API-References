---
title: "Event.PreventDefault"
second_title: "Aspose.HTML för Java API-referens"
description: "Event‑metod. Om en händelse kan avbrytas används PreventDefault‑metoden för att ange att händelsen ska avbrytas, vilket betyder att någon standardåtgärd som normalt utförs av implementationen som ett resultat av händelsen inte kommer att ske."
type: docs

url: /sv/java/com.aspose.html.dom.events/event/preventdefault/
---
## Event.PreventDefault method

Om en händelse kan avbrytas används `PreventDefault`‑metoden för att ange att händelsen ska avbrytas, vilket betyder att någon standardåtgärd som normalt utförs av implementationen som ett resultat av händelsen inte kommer att ske.

```java
public void PreventDefault()
```

## Anmärkningar

Om, under någon fas av händelseflödet, `PreventDefault`‑metoden anropas avbryts händelsen. Alla standardåtgärder som är kopplade till händelsen kommer inte att ske. Att anropa denna metod för en icke‑avbrytbar händelse har ingen effekt. När `PreventDefault` har anropats kommer den att fortsätta gälla under resten av händelsens spridning. Denna metod kan användas under vilken fas av händelseflödet som helst.

### Se även

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
