---
title: Document.CreateEvent
second_title: Aspose.HTML für .NET-API-Referenz
description: Document methode. Erstellt eineEvent eines Typs der von der Implementierung unterstützt wird.
type: docs
weight: 880
url: /de/net/aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

Erstellt eine[`Event`](../../../aspose.html.dom.events/event/) eines Typs, der von der Implementierung unterstützt wird.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| eventType | String | Der Parameter eventType gibt den Typ von an[`Event`](../../../aspose.html.dom.events/event/) zu erstellende Schnittstelle.  Wenn die[`Event`](../../../aspose.html.dom.events/event/) Die angegebene Schnittstelle wird von der Implementierung unterstützt. Diese Methode wird eine neue zurückgeben[`Event`](../../../aspose.html.dom.events/event/) des angeforderten Schnittstellentyps. Wenn die[`Event`](../../../aspose.html.dom.events/event/)soll per versendet werden[`DispatchEvent`](../../../aspose.html.dom.events/ieventtarget/dispatchevent/) Methode die passende[`InitEvent`](../../../aspose.html.dom.events/event/initevent/) -Methode muss nach der Erstellung aufgerufen werden, um die zu initialisieren[`Event`](../../../aspose.html.dom.events/event/) s-Werte. |

### Rückgabewert

Die neu erstellte[`Event`](../../../aspose.html.dom.events/event/)

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn die Implementierung den Typ von nicht unterstützt[`Event`](../../../aspose.html.dom.events/event/) Schnittstelle angefordert |

### Siehe auch

* class [Event](../../../aspose.html.dom.events/event/)
* class [Document](../)
* namensraum [Aspose.Html.Dom](../../document/)
* Montage [Aspose.HTML](../../../)


