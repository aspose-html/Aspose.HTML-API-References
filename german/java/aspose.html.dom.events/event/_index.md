---
title: "Event‑Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.events.Event‑Klasse. Sie wird verwendet, um kontextbezogene Informationen über ein Ereignis dem Handler, der das Ereignis verarbeitet, bereitzustellen."
type: docs

url: /de/java/com.aspose.html.dom.events/event/
---
## Event class

Dies wird verwendet, um kontextbezogene Informationen über ein Ereignis an den Handler, der das Ereignis verarbeitet, zu liefern.

```java
public class Event : DOMObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Event](event/#constructor)(String) | Initialisiert eine neue Instanz der `Event`‑Klasse. |
| [Event](event/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Wird verwendet, um anzuzeigen, ob ein Ereignis ein Bubbling‑Ereignis ist. Wenn das Ereignis bubbling unterstützt, ist der Wert true, sonst false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Wird verwendet, um anzuzeigen, ob ein Ereignis seine Standardaktion verhindern kann. Wenn die Standardaktion verhindert werden kann, ist der Wert true, sonst false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Wird verwendet, um das [`IEventTarget`](../ieventtarget/) anzuzeigen, dessen [`IEventListener`](../ieventlistener/)s gerade verarbeitet werden. Dies ist besonders nützlich während des Capturing und Bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Gibt true zurück, wenn preventDefault() aufgerufen wurde, während das cancelable‑Attribut true ist, andernfalls false. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Wird verwendet, um anzuzeigen, welche Phase des Ereignisflusses derzeit ausgewertet wird. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Das Attribut isTrusted muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf false initialisiert werden. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Wird verwendet, um das [`IEventTarget`](../ieventtarget/) anzugeben, an das das Ereignis ursprünglich gesendet wurde. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Wird verwendet, um die Zeit (in Millisekunden relativ zum Epoch) anzugeben, zu der das Ereignis erstellt wurde. Da einige Systeme diese Information möglicherweise nicht bereitstellen, kann der Wert von timeStamp für nicht alle Ereignisse verfügbar sein. Wenn nicht verfügbar, wird ein Wert von 0 zurückgegeben. Beispiele für Epoch‑Zeit sind der Systemstart oder 0:0:0 UTC, 1. Januar 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Der Name des Ereignisses (Groß-/Kleinschreibung wird ignoriert). Der Name muss ein XML‑Name sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript-Objekt abzurufen. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Die [`InitEvent`](./initevent/)‑Methode wird verwendet, um den Wert eines über die[`IDocumentEvent`](../idocumentevent/)‑Schnittstelle erstellten `Event` zu initialisieren. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Ist ein Ereignis abbrechbar, wird die [`PreventDefault`](./preventdefault/)‑Methode verwendet, um anzuzeigen, dass das Ereignis abgebrochen werden soll, d. h. dass keine Standardaktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt würde, erfolgt. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Der Aufruf dieser Methode verhindert, dass das Ereignis an Ereignis‑Listener gelangt, die nach dem aktuellen registriert wurden, und verhindert beim Versand in einem Baum, dass das Ereignis andere Objekte erreicht. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Die [`StopPropagation`](./stoppropagation/)‑Methode wird verwendet, um die weitere Weiterleitung eines Ereignisses während des Ereignisflusses zu verhindern. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [AtTargetPhase](../../com.aspose.html.dom.events/event/attargetphase/) | Die aktuelle Ereignisphase ist die Erfassungsphase. |
| const [BubblingPhase](../../com.aspose.html.dom.events/event/bubblingphase/) | Die aktuelle Ereignisphase ist die Aufstiegsphase. |
| const [CapturingPhase](../../com.aspose.html.dom.events/event/capturingphase/) | Das Ereignis wird derzeit am Ziel [`IEventTarget`](../ieventtarget/) ausgewertet. |
| const [NonePhase](../../com.aspose.html.dom.events/event/nonephase/) | Ereignisse, die derzeit nicht ausgelöst werden, befinden sich in dieser Phase. |

## Hinweise

Ein Objekt, das die Schnittstelle implementiert, wird in der Regel als erster Parameter an einen Ereignishandler übergeben. Weiterführende Kontextinformationen werden an Ereignishandler übergeben, indem zusätzliche Schnittstellen abgeleitet werden, die Informationen enthalten, die sich direkt auf den Typ des begleitenden Ereignisses beziehen. Diese abgeleiteten Schnittstellen werden ebenfalls von dem an den Ereignislistener übergebenen Objekt implementiert.

### Siehe auch

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
