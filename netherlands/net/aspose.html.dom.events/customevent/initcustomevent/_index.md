---
title: CustomEvent.InitCustomEvent
second_title: Aspose.HTML voor .NET API-referentie
description: CustomEvent methode. /// DeInitEvent methode wordt gebruikt om de waarde van een te initialiserenEvent gemaakt door deIDocumentEvent interface.
type: docs
weight: 30
url: /nl/net/aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// De[`InitEvent`](../../event/initevent/) methode wordt gebruikt om de waarde van een te initialiseren[`Event`](../../event/) gemaakt door de[`IDocumentEvent`](../../idocumentevent/) interface.

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Het gebeurtenistype. |
| bubbles | Boolean | indien ingesteld op`WAAR` [bubbels]. |
| cancelable | Boolean | indien ingesteld op`WAAR` [opzegbaar]. |
| detail | Object | De aangepaste gegevens. |

### Opmerkingen

Deze methode mag alleen worden aangeroepen voordat de gebeurtenis is verzonden via de[`DispatchEvent`](../../ieventtarget/dispatchevent/) methode, hoewel het tijdens die fase indien nodig meerdere keren kan worden aangeroepen. Als het meerdere keren wordt aangeroepen, heeft de uiteindelijke aanroep voorrang. Als het wordt aangeroepen vanuit een subklasse van de Event-interface, worden alleen de waarden die zijn opgegeven in de initEvent-methode gewijzigd, alle andere attributen blijven ongewijzigd.

### Zie ook

* class [CustomEvent](../)
* naamruimte [Aspose.Html.Dom.Events](../../customevent/)
* montage [Aspose.HTML](../../../)


