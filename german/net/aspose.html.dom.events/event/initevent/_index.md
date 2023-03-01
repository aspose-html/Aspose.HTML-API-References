---
title: Event.InitEvent
second_title: Aspose.HTML für .NET-API-Referenz
description: Event methode. DieInitEvent Methode wird verwendet um den Wert von an zu initialisierenEvent erstellt durch the IDocumentEvent Schnittstelle.
type: docs
weight: 110
url: /de/net/aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

Die`InitEvent` -Methode wird verwendet, um den Wert von an zu initialisieren[`Event`](../) erstellt durch the [`IDocumentEvent`](../../idocumentevent/) Schnittstelle.

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Der Ereignistyp. |
| bubbles | Boolean | wenn eingestellt`WAHR` [Blasen]. |
| cancelable | Boolean | wenn eingestellt`WAHR` [kündbar]. |

### Bemerkungen

Diese Methode darf nur aufgerufen werden, bevor das Event über die versendet wurde[`DispatchEvent`](../../ieventtarget/dispatchevent/) Methode, obwohl sie während dieser Phase bei Bedarf mehrmals aufgerufen werden kann. Wenn sie mehrmals aufgerufen wird, hat der letzte Aufruf Vorrang. Wenn sie von einer Unterklasse der Event-Schnittstelle aufgerufen wird, werden nur die in der initEvent-Methode angegebenen Werte geändert, alle anderen Attribute bleiben unverändert.

### Siehe auch

* class [Event](../)
* namensraum [Aspose.Html.Dom.Events](../../event/)
* Montage [Aspose.HTML](../../../)


