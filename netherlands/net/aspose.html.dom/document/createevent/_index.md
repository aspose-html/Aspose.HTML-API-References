---
title: Document.CreateEvent
second_title: Aspose.HTML voor .NET API-referentie
description: Document methode. Creëert eenEvent van een type dat wordt ondersteund door de implementatie.
type: docs
weight: 880
url: /nl/net/aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

Creëert een[`Event`](../../../aspose.html.dom.events/event/) van een type dat wordt ondersteund door de implementatie.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eventType | String | De parameter eventType specificeert het type van[`Event`](../../../aspose.html.dom.events/event/) aan te maken interface.  Als de[`Event`](../../../aspose.html.dom.events/event/) opgegeven interface wordt ondersteund door de implementatie deze methode will retourneert een nieuw[`Event`](../../../aspose.html.dom.events/event/) van het aangevraagde interfacetype. Als de[`Event`](../../../aspose.html.dom.events/event/)wordt verzonden via de[`DispatchEvent`](../../../aspose.html.dom.events/ieventtarget/dispatchevent/) methode de juiste[`InitEvent`](../../../aspose.html.dom.events/event/initevent/) De methode moet na het maken worden aangeroepen om het[`Event`](../../../aspose.html.dom.events/event/) s waarden. |

### Winstwaarde

De nieuw gemaakte[`Event`](../../../aspose.html.dom.events/event/)

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Verhoogd als de implementatie het type van niet ondersteunt[`Event`](../../../aspose.html.dom.events/event/) interface gevraagd |

### Zie ook

* class [Event](../../../aspose.html.dom.events/event/)
* class [Document](../)
* naamruimte [Aspose.Html.Dom](../../document/)
* montage [Aspose.HTML](../../../)


