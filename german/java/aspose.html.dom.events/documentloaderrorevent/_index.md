---
title: "DocumentLoadErrorEvent Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.events.DocumentLoadErrorEvent class. Das DocumentLoadErrorEvent tritt auf, wenn die angeforderte Ressource nicht verfügbar ist"
type: docs

url: /de/java/com.aspose.html.dom.events/documentloaderrorevent/
---
## DocumentLoadErrorEvent class

Das DocumentLoadErrorEvent tritt auf, wenn die angeforderte Ressource nicht verfügbar ist.

```java
public class DocumentLoadErrorEvent : ErrorEvent
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Wird verwendet, um anzugeben, ob ein Ereignis ein Bubbling‑Ereignis ist oder nicht. Wenn das Ereignis bubbling‑fähig ist, ist der Wert true, sonst false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Wird verwendet, um anzugeben, ob die Standardaktion eines Ereignisses verhindert werden kann. Wenn die Standardaktion verhindert werden kann, ist der Wert true, sonst false. |
| [getColNo](../../com.aspose.html.dom.events/errorevent/colno/) Das Attribut colno muss den Wert zurückgeben, mit dem es initialisiert wurde. Beim Erzeugen des Objekts muss dieses Attribut auf Null initialisiert werden. Es stellt die Spaltennummer dar, in der der Fehler im Skript aufgetreten ist. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Wird verwendet, um das [`IEventTarget`](../ieventtarget/) anzugeben, dessen [`IEventListener`](../ieventlistener/) gerade verarbeitet werden. Dies ist besonders nützlich während des Capturing‑ und Bubbling‑Phasen. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Gibt true zurück, wenn preventDefault() aufgerufen wurde, während das Attribut cancelable den Wert true hat, andernfalls false. |
| [getError](../../com.aspose.html.dom.events/errorevent/error/) Das Attribut error muss den Wert zurückgeben, mit dem es initialisiert wurde. Beim Erzeugen des Objekts muss dieses Attribut auf null initialisiert werden. Bei Bedarf wird es auf das Objekt gesetzt, das den Fehler darstellt (z. B. das Ausnahmeobjekt im Fall einer nicht abgefangenen DOM‑Ausnahme). |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Wird verwendet, um anzugeben, welche Phase des Ereignisflusses derzeit ausgewertet wird. |
| [getFileName](../../com.aspose.html.dom.events/errorevent/filename/) Das Attribut filename muss den Wert zurückgeben, mit dem es initialisiert wurde. Beim Erzeugen des Objekts muss dieses Attribut auf die leere Zeichenkette initialisiert werden. Es stellt die absolute URL des Skripts dar, in dem der Fehler ursprünglich aufgetreten ist. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Das isTrusted-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn ein Ereignis erstellt wird, muss das Attribut auf false initialisiert werden. |
| [getLineNo](../../com.aspose.html.dom.events/errorevent/lineno/) Das lineno-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn das Objekt erstellt wird, muss dieses Attribut auf 0 initialisiert werden. Es stellt die Zeilennummer dar, in der der Fehler im Skript aufgetreten ist. |
| [getMessage](../../com.aspose.html.dom.events/errorevent/message/) Das message-Attribut muss den Wert zurückgeben, mit dem es initialisiert wurde. Wenn das Objekt erstellt wird, muss dieses Attribut auf die leere Zeichenkette initialisiert werden. Es stellt die Fehlermeldung dar. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Wird verwendet, um das [`IEventTarget`](../ieventtarget/) anzugeben, an das das Ereignis ursprünglich gesendet wurde. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Wird verwendet, um die Zeit (in Millisekunden relativ zum Epoch) anzugeben, zu der das Ereignis erstellt wurde. Da einige Systeme diese Information möglicherweise nicht bereitstellen, kann der Wert von timeStamp für nicht alle Ereignisse verfügbar sein. Wenn nicht verfügbar, wird ein Wert von 0 zurückgegeben. Beispiele für Epoch‑Zeit sind die Systemstartzeit oder 0:0:0 UTC, 1. Januar 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Der Name des Ereignisses (Groß‑/Kleinschreibung ignorierend). Der Name muss ein XML‑Name sein. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um das ECMAScript‑Objekt abzurufen. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Die Methode [`InitEvent`](../event/initevent/) wird verwendet, um den Wert eines über die[`IDocumentEvent`](../idocumentevent/)‑Schnittstelle erstellten [`Event`](../event/) zu initialisieren. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Wenn ein Ereignis abbrechbar ist, wird die Methode [`PreventDefault`](../event/preventdefault/) verwendet, um anzuzeigen, dass das Ereignis abgebrochen werden soll, d. h. jede Standardaktion, die normalerweise von der Implementierung als Ergebnis des Ereignisses ausgeführt würde, findet nicht statt. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Der Aufruf dieser Methode verhindert, dass das Ereignis an Ereignislistener gelangt, die nach dem aktuellen registriert wurden, und verhindert beim Versand in einem Baum, dass das Ereignis andere Objekte erreicht. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Die Methode [`StopPropagation`](../event/stoppropagation/) wird verwendet, um die weitere Ausbreitung eines Ereignisses während des Ereignisflusses zu verhindern. |

### Siehe auch

* class [ErrorEvent](../errorevent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
