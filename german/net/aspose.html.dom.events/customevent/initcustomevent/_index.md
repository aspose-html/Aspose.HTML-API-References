---
title: CustomEvent.InitCustomEvent
second_title: Aspose.HTML für .NET-API-Referenz
description: CustomEvent methode. /// DieInitEvent Methode wird verwendet um den Wert von an zu initialisierenEvent erstellt durch dieIDocumentEvent Schnittstelle.
type: docs
weight: 30
url: /de/net/aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// Die[`InitEvent`](../../event/initevent/) -Methode wird verwendet, um den Wert von an zu initialisieren[`Event`](../../event/) erstellt durch die[`IDocumentEvent`](../../idocumentevent/) Schnittstelle.

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Der Ereignistyp. |
| bubbles | Boolean | wenn eingestellt`WAHR` [Blasen]. |
| cancelable | Boolean | wenn eingestellt`WAHR` [kündbar]. |
| detail | Object | Die benutzerdefinierten Daten. |

### Bemerkungen

Diese Methode darf nur aufgerufen werden, bevor das Event über die versendet wurde[`DispatchEvent`](../../ieventtarget/dispatchevent/) Methode, obwohl sie während dieser Phase bei Bedarf mehrmals aufgerufen werden kann. Wenn sie mehrmals aufgerufen wird, hat der letzte Aufruf Vorrang. Wenn sie von einer Unterklasse der Event-Schnittstelle aufgerufen wird, werden nur die in der initEvent-Methode angegebenen Werte geändert, alle anderen Attribute bleiben unverändert.

### Siehe auch

* class [CustomEvent](../)
* namensraum [Aspose.Html.Dom.Events](../../customevent/)
* Montage [Aspose.HTML](../../../)


