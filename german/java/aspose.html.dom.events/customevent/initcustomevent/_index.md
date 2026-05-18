---
title: "CustomEvent.InitCustomEvent"
second_title: "Aspose.HTML für Java API-Referenz"
description: "CustomEvent-Methode. /// Die InitEvent-Methode wird verwendet, um den Wert eines Ereignisses zu initialisieren, das über die IDocumentEvent-Schnittstelle erstellt wurde."
type: docs

url: /de/java/com.aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// Die [`InitEvent`](../../event/initevent/)-Methode wird verwendet, um den Wert eines [`Event`](../../event/) zu initialisieren, das über die [`IDocumentEvent`](../../idocumentevent/)-Schnittstelle erstellt wurde.

```java
public void InitCustomEvent(String type, bool bubbles, bool cancelable, object detail)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | String | Der Ereignistyp. |
| bubbles | Boolean | wenn auf `true` [bubbles] gesetzt. |
| cancelable | Boolean | wenn auf `true` [cancelable] gesetzt. |
| detail | Objekt | Die benutzerdefinierten Daten. |

## Hinweise

Diese Methode darf nur aufgerufen werden, bevor das Event über die [`DispatchEvent`](../../ieventtarget/dispatchevent/)-Methode ausgelöst wurde, kann jedoch bei Bedarf während dieser Phase mehrfach aufgerufen werden. Bei mehrfachen Aufrufen hat der letzte Aufruf Vorrang. Wird sie von einer Unterklasse der Event-Schnittstelle aufgerufen, werden nur die im initEvent-Methode angegebenen Werte geändert, alle anderen Attribute bleiben unverändert.

### Siehe auch

* class [CustomEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
