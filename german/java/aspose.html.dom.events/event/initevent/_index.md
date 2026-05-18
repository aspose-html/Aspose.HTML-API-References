---
title: "Event.InitEvent"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Ereignismethode. Die InitEvent-Methode wird verwendet, um den Wert eines Event zu initialisieren, das über die IDocumentEvent-Schnittstelle erstellt wurde."
type: docs

url: /de/java/com.aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

Die `InitEvent`-Methode wird verwendet, um den Wert eines [`Event`](../) zu initialisieren, das über die [`IDocumentEvent`](../../idocumentevent/) Schnittstelle erstellt wurde.

```java
public void InitEvent(String type, bool bubbles, bool cancelable)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | String | Der Ereignistyp. |
| bubbles | Boolean | wenn auf `true` [bubbles] gesetzt. |
| cancelable | Boolean | wenn auf `true` [cancelable] gesetzt. |

## Hinweise

Diese Methode darf nur aufgerufen werden, bevor das Event über die [`DispatchEvent`](../../ieventtarget/dispatchevent/)-Methode ausgelöst wurde, kann jedoch bei Bedarf während dieser Phase mehrfach aufgerufen werden. Bei mehrfachen Aufrufen hat der letzte Aufruf Vorrang. Wird sie von einer Unterklasse der Event-Schnittstelle aufgerufen, werden nur die im initEvent-Methode angegebenen Werte geändert, alle anderen Attribute bleiben unverändert.

### Siehe auch

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
