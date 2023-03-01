---
title: IDocumentEvent.CreateEvent
second_title: Aspose.HTML voor .NET API-referentie
description: IDocumentEvent methode. Creëert eenEvent van een type dat wordt ondersteund door de implementatie.
type: docs
weight: 10
url: /nl/net/aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Creëert een[`Event`](../../event/) van een type dat wordt ondersteund door de implementatie.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eventType | String | De parameter eventType specificeert het type van[`Event`](../../event/) aan te maken interface.  Als de[`Event`](../../event/)gespecificeerde interface wordt ondersteund door de implementatie deze methode retourneert een new [`Event`](../../event/) van het aangevraagde interfacetype. Als de[`Event`](../../event/)wordt verzonden via de[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) methode de juiste [`InitEvent`](../../event/initevent/) methode moet na het maken worden aangeroepen om het[`Event`](../../event/) s waarden. |

### Winstwaarde

De nieuw gemaakte[`Event`](../../event/)

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Verhoogd als de implementatie het type[`Event`](../../event/) interface aangevraagd |

### Zie ook

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* naamruimte [Aspose.Html.Dom.Events](../../idocumentevent/)
* montage [Aspose.HTML](../../../)


