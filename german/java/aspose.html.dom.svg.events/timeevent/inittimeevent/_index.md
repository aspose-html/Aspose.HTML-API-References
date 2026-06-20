---
title: "TimeEvent.InitTimeEvent"
second_title: "Aspose.HTML für Java API-Referenz"
description: "TimeEvent-Methode. Die initTimeEvent-Methode wird verwendet, um den Wert eines über die DocumentEvent-Schnittstelle erstellten TimeEvent zu initialisieren. Diese Methode darf nur aufgerufen werden, bevor das TimeEvent über die dispatchEvent-Methode gesendet wurde, kann jedoch in dieser Phase bei Bedarf mehrmals aufgerufen werden. Wird sie mehrmals aufgerufen, hat der letzte Aufruf Vorrang."
type: docs

url: /de/java/com.aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

Die initTimeEvent-Methode wird verwendet, um den Wert eines über die DocumentEvent-Schnittstelle erstellten TimeEvent zu initialisieren. Diese Methode darf nur aufgerufen werden, bevor das TimeEvent über die dispatchEvent-Methode gesendet wurde, kann jedoch bei Bedarf während dieser Phase mehrfach aufgerufen werden. Wird sie mehrfach aufgerufen, hat der letzte Aufruf Vorrang.

```java
public void InitTimeEvent(String typeArg, IAbstractView viewArg, long detailArg)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeArg | String | Gibt den Ereignistyp an. |
| viewArg | IAbstractView | Gibt die AbstractView des Ereignisses an. |
| detailArg | Int64 | Gibt das Detail des Ereignisses an. |

### Siehe auch

* interface [IAbstractView](../../../com.aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* package [com.aspose.html.dom.svg.events](../../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../../)
