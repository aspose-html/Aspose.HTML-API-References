---
title: "TimeEvent-Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.svg.events.TimeEvent-Klasse. Das TimeEvent-Interface liefert spezifische Kontextinformationen, die mit Zeitereignissen verbunden sind. Die verschiedenen Arten von Ereignissen, die auftreten können, sind beginEvent, endEvent und repeatEvent."
type: docs

url: /de/java/com.aspose.html.dom.svg.events/timeevent/
---
## TimeEvent class

Das TimeEvent-Interface liefert spezifische Kontextinformationen, die mit Zeitereignissen verbunden sind. Die verschiedenen Ereignistypen, die auftreten können, sind: beginEvent, endEvent und repeatEvent.

```java
public class TimeEvent : Event
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Wird verwendet, um anzuzeigen, ob ein Ereignis ein Bubbling‑Ereignis ist. Wenn das Ereignis bubbling unterstützt, ist der Wert true, sonst false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Wird verwendet, um anzuzeigen, ob ein Ereignis seine Standardaktion verhindern kann. Wenn die Standardaktion verhindert werden kann, ist der Wert true, sonst false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Wird verwendet, um das [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) anzugeben, dessen [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/)s gerade verarbeitet werden. Dies ist besonders nützlich während des Capturing und Bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Gibt true zurück, wenn preventDefault() aufgerufen wurde, während das cancelable‑Attribut true ist, andernfalls false. |
| [getDetail](../../com.aspose.html.dom.svg.events/timeevent/detail/) Gibt einige Detailinformationen über das Ereignis an, abhängig vom Typ des Ereignisses. Für diesen Ereignistyp gibt es die Wiederholungszahl für die Animation an. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Wird verwendet, um anzuzeigen, welche Phase des Ereignisflusses derzeit ausgewertet wird. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Das Attribut isTrusted muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf false initialisiert werden. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Wird verwendet, um das [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) anzugeben, an das das Ereignis ursprünglich gesendet wurde. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Wird verwendet, um die Zeit (in Millisekunden relativ zum Epoch) anzugeben, zu der das Ereignis erstellt wurde. Da einige Systeme diese Information möglicherweise nicht bereitstellen, kann der Wert von timeStamp für nicht alle Ereignisse verfügbar sein. Wenn nicht verfügbar, wird ein Wert von 0 zurückgegeben. Beispiele für Epoch‑Zeit sind der Systemstart oder 0:0:0 UTC, 1. Januar 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Der Name des Ereignisses (Groß-/Kleinschreibung wird ignoriert). Der Name muss ein XML‑Name sein. |
| [getView](../../com.aspose.html.dom.svg.events/timeevent/view/) Das view-Attribut identifiziert die AbstractView [DOM2VIEWS], aus der das Ereignis erzeugt wurde. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript-Objekt abzurufen. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Die [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) Methode wird verwendet, um den Wert eines über die [`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/) Schnittstelle erstellten [`Event`](../../com.aspose.html.dom.events/event/) zu initialisieren. |
| [initTimeEvent](../../com.aspose.html.dom.svg.events/timeevent/inittimeevent/)(String, IAbstractView, long) | Die initTimeEvent-Methode wird verwendet, um den Wert eines über die DocumentEvent-Schnittstelle erstellten TimeEvent zu initialisieren. Diese Methode darf nur aufgerufen werden, bevor das TimeEvent über die dispatchEvent-Methode gesendet wurde, kann jedoch bei Bedarf während dieser Phase mehrfach aufgerufen werden. Wird sie mehrfach aufgerufen, hat der letzte Aufruf Vorrang. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Wenn ein Ereignis abbrechbar ist, wird die [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) Methode verwendet, um anzuzeigen, dass das Ereignis abgebrochen werden soll, sodass jede standardmäßige Aktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt wird, nicht stattfindet. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Der Aufruf dieser Methode verhindert, dass das Ereignis an Ereignis‑Listener gelangt, die nach dem aktuellen registriert wurden, und verhindert beim Versand in einem Baum, dass das Ereignis andere Objekte erreicht. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Die [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) Methode wird verwendet, um die weitere Weiterleitung eines Ereignisses während des Ereignisflusses zu verhindern. |

### Siehe auch

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
