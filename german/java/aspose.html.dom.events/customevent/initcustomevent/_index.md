---
title: "CustomEvent.InitCustomEvent"
second_title: "Aspose.HTML für Java API-Referenz"
description: "CustomEvent-Methode. /// Die InitEvent-Methode wird verwendet, um den Wert eines über die IDocumentEvent-Schnittstelle erstellten Events zu initialisieren."
type: docs

url: /de/java/com.aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// Die [`InitEvent`](../../event/initevent/) Methode wird verwendet, um den Wert eines über die [`IDocumentEvent`](../../idocumentevent/) Schnittstelle erstellten [`Event`](../../event/) zu initialisieren.

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

Diese Methode darf nur aufgerufen werden, bevor das Event über die [`DispatchEvent`](../../ieventtarget/dispatchevent/)‑Methode ausgelöst wurde, obwohl sie bei Bedarf während dieser Phase mehrfach aufgerufen werden kann. Wird sie mehrfach aufgerufen, hat der letzte Aufruf Vorrang. Wird sie von einer Unterklasse der Event‑Schnittstelle aufgerufen, werden nur die im initEvent‑Verfahren angegebenen Werte geändert, alle anderen Attribute bleiben unverändert.

### Siehe auch

* class [CustomEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
