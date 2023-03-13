---
title: Event.InitEvent
second_title: Aspose.HTML voor .NET API-referentie
description: Event methode. DeInitEvent methode wordt gebruikt om de waarde van een te initialiserenEvent gemaakt door the IDocumentEvent interface.
type: docs
weight: 110
url: /nl/net/aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

De`InitEvent` methode wordt gebruikt om de waarde van een te initialiseren[`Event`](../) gemaakt door the [`IDocumentEvent`](../../idocumentevent/) interface.

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Het gebeurtenistype. |
| bubbles | Boolean | indien ingesteld op`WAAR` [bubbels]. |
| cancelable | Boolean | indien ingesteld op`WAAR` [opzegbaar]. |

### Opmerkingen

Deze methode mag alleen worden aangeroepen voordat de gebeurtenis is verzonden via de[`DispatchEvent`](../../ieventtarget/dispatchevent/) methode, hoewel het tijdens die fase indien nodig meerdere keren kan worden aangeroepen. Als het meerdere keren wordt aangeroepen, heeft de uiteindelijke aanroep voorrang. Als het wordt aangeroepen vanuit een subklasse van de Event-interface, worden alleen de waarden die zijn opgegeven in de initEvent-methode gewijzigd, alle andere attributen blijven ongewijzigd.

### Zie ook

* class [Event](../)
* naamruimte [Aspose.Html.Dom.Events](../../event/)
* montage [Aspose.HTML](../../../)


